# poutine-action

This is a simple GitHub Action to simplify using poutine as part of GitHub Actions workflows.

Created by BoostSecurity.io, poutine is a security scanner that detects misconfigurations and vulnerabilities in the build pipelines of a repository. It supports parsing CI workflows from GitHub Actions and Gitlab CI/CD. When given an access token with read-level access, poutine can analyze all the repositories of an organization to quickly gain insights into the security posture of the organization's software supply chain.

Visit https://github.com/boostsecurityio/poutine for more details about poutine itself.

## Privacy

This Action contacts Chainguard's licensing server to verify authorization. Connection metadata (IP address, GitHub repository identifier, timestamp, and any metadata encoded in the auth token) is transmitted to Chainguard, Inc. even if authorization is denied in accordance with our [Privacy Notice](https://www.chainguard.dev/legal/privacy-notice)
