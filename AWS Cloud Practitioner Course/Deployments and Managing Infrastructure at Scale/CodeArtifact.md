- A secure, scalable, and cost-effective artifact management system for software development
- Software packages depend on each other to be built (also called code dependencies) as new ones are created
- Storing and retrieving these dependencies is called artifact management
- Traditionally you need to setup your own artifact management system
- Works with common dependency management tools such as
	- Maven
	- Gradle
	- NPM
	- Yarn
	- Twine
	- Pip
	- NuGet
- Developers and CodeBuild can then retrieve dependencies straight from CodeArtifact
- This is basically NuGet for us