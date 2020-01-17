# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.0.1
### Added
- Initial relase based on the great extension: https://github.com/rv-csanford/scss-block-comments-vscode. This one is too specific to Sass and will not run when using PostCSS for a few reasons. 1) It only looks for PostCSS so it require manual activation every time and 2) The comments being used // do not work in regular CSS. So this new extension uses /* */.
- Only supports PostCSS without manual activation for now.