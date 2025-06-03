# AdvancedConsole

**Advanced Console** is a lightweight C# library that enhances the standard `Console.Write` and `Console.WriteLine` methods with performance optimizations and powerful text formatting features and a plugin based inline command system.

## Overview

*   [About this project](#about)
    *   [Why?](#why?)
    *   [Main Features](#main-features)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Creating your own Commands](#dingus)
*   [Contributing](#contributing)
*   [License](#license)

## About

### Why?

While the C# console is rarely used for full applications, it's often the starting point for many developers — and there's a certain charm to its simplicity that's worth preserving.  
This project is built around improving that simplicity while adding more functionality.

### Main Features

*   **Write Batching:**  
Reduces the overhead of multiple Write calls by batching them into a single flush operation.  
Improves performance in output-heavy scenarios.

*   **Modular Command System:**  
Inspired loosely by HTML-style syntax, allowing you to embed commands directly into strings. Example:  
`AConsole.Write("Hello <color:red>World</color>!");`  
The command system is fully modular—easy to extend with custom commands that can do much more than just styling.

## Contributing

Feel free to help! [Open an issue](https://https://github.com/NineOfGaming/AdvancedConsole/issues/new) or submit PRs.

### Contributors
Thanks to all the people who contribute.

<a href="https://github.com/NineOfGaming/AdvancedConsole/graphs/contributors">
<img src="https://contrib.rocks/image?repo=NineOfGaming/AdvancedConsole" />
</a>

## License

This project is licensed under the GNU General Public License v3.0 - see the <a href="./LICENSE">LICENSE</a> file for details.
