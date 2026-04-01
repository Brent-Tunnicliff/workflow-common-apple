# workflow-common-apple

Common workflow pipelines for apple and swift projects.

## Workflows:

### xcodebuild

Builds and runs tests for input project using xcodebuild.

Checks git status at the end to make sure that no unhandled generated files are present.

### swift

Builds and runs tests for input project using swift.

Checks git status at the end to make sure that no unhandled generated files are present.

### lint

Runs strict swift lint for the whole repository.

### documentation

Builds the documentation using swift package generate-documentation.

For this to work the project needs to add <https://github.com/swiftlang/swift-docc-plugin> to its dependencies so we can use the command plugin.

## Disclaimer

This project is open source and open to anyone to use as they see fit.

But I am building this with myself as the main target audience, so this will not be published anywhere.
