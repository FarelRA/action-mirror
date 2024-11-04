# GitHub Action for Mirroring Artifacts

This GitHub Action makes it easy to mirror files and artifacts from URLs directly within your workflows. It uses `aria2` for optimized, parallel downloads and supports custom headers for authentication or other specific needs.

## Features

* **Fast Downloads with aria2:** Leverages aria2's multi-connection and segmented downloading capabilities for significantly faster transfers.
* **Parallel Downloads:** Downloads multiple files concurrently for improved speed and efficiency.
* **Custom Headers:** Supports adding custom headers to download requests (e.g., for authentication or accessing private resources).
* **Artifact Uploads:** Automatically uploads the mirrored files as GitHub artifacts for easy access in your workflow.
* **Easy Configuration:** Simple inputs for URLs, artifact names, and custom headers.
