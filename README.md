# Discord ModuleController *(Public Alpha Test)*

<div align="center">
	<br />
	<p>
		<a href="https://www.npmjs.com/package/discord-modulecontroller"><img src="https://img.shields.io/npm/v/discord-modulecontroller.svg?maxAge=3600" alt="npm version" /></a>
		<a href="https://www.npmjs.com/package/discord-modulecontroller"><img src="https://img.shields.io/npm/dt/discord-modulecontroller.svg" alt="npm downloads" /></a>
		<a href="https://www.npmjs.com/package/discord-modulecontroller"><img src="https://img.shields.io/npm/last-update/discord-modulecontroller" alt="npm update" /></a>
	</p>
</div>

## Description
ModuleController is an **Alpha Test** for managing Discord bot modules, allowing you to dynamically load, configure, and manage various parts of your bot's functionality. This is an ongoing test phase, and the API may change.

## Features
- Dynamic module loading and configuration.
- Supports different types of modules (commands, events, contextmenus, buttons, etc.).
- Auto-completion support for module management.

### Functions Overview
Here are some of the key functions provided by `ModuleController`:
- **ClientInit**: Initializes the ModuleController and defines module management.
- **getModuleChoices(client)**: Returns module types (used for AutoComplete).
- **getModulesByType(client, type, keyword)**: Fetches the list of modules based on the type and keyword for search functionality.
- **getUnloadedModulesByType(client, type, keyword)**: Fetches the list of unloaded modules based on the type and keyword.
- **getNotLoadedModuleChoices(client)**: Returns module types for modules that haven't been loaded yet.
- **getModulePath(moduleType, moduleName)**: Returns the full path of the module based on type and name.
- **ModuleFileLoader(client, moduleType, filePath)**: Loads the module from the specified path.
- **TEST_unloadModuleFile(client, moduleType, filePath)**: Unloads the module from the specified path.

## Contributing
At the moment, contributing through issues or pull requests is not available. However, this feature will be added in the future.

## License
Apache-2.0

## Contact
For any questions or feedback, feel free to contact us at:  
**Email**: [support@zrs.hu](mailto:support@zrs.hu)  
**Website**: [https://zrs.hu](https://zrs.hu)
