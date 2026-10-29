# Universal build tooling

Public, application-independent Python/Node build environment. This repository contains no private application source, credentials, production configuration or customer data.

The workflow builds and smoke-tests the generic tool image only. Private application checks and release authorization remain in the private project's trusted release process. Calling this workflow from a private repository does not move the caller's billing context. Do not upload private build logs or application artifacts here.
