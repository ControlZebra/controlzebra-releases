# Changelog

All notable customer-facing changes are documented here.

This changelog follows a stable structure for every release:
- Added
- Improved
- Fixed
- Known Limitations

## 0.0.1

First customer release.

### Added

- Next Step Advisor in the sidebar to guide users with clear actions such as 
    - `Start Tracking` 
    - `Push Changes` 
    - `Publish to Cloud`
    - `I am ready to merge`.
- Guided Git onboarding for local tracking, plus package readiness checks for Git and Git LFS.
- Commit and working-change workflow with file-level change visibility and diff access.
- Visual diff support for industrial files, including ladder logic (`.l5x`, `.l5k`) and PDF documents.
- History experience with both commit list and branch graph views.
- Merge workflow with conflict checking, selective review, guided resolution, and completion flow.
- GitHub publish and authentication flow for cloud backup and team collaboration.

### Improved

- Language and UI actions tuned for non-technical and mixed-skill automation teams.
- Safer default workflows for branch usage and merge preparation.

### Fixed

- N/A for initial public release.

### Known Limitations

- Some UI elements like 'Publish to GitHub' do not update in real time. They will update when you load the project again.
- Some advanced Git operations still use technical terms in specific screens.
- Support is optimized for desktop-first workflows and may vary by artifact complexity.
