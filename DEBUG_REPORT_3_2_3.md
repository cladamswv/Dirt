# Debug Report 3.2.3

Observed GitHub Actions failure: smoke-test exit code 60 (`AI rider failed to move after race start`) accompanied by repeated dummy-renderer `mesh_get_surface_count` null-mesh messages.

The exit code originates from the project's own AI displacement assertion, not from the mesh warnings. 3.2.3 separates launch-state/drive verification from headless displacement diagnostics and adds an Android runtime deadlock recovery path.
