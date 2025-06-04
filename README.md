# AdvancedConsole

**Advanced Console** is a C# library that enhances the standard `Console.Write` and `Console.WriteLine` methods with performance optimizations, advanced text formatting, and a plugin-based inline command system.

## Overview

*   [About this project](#about)
    *   [Why?](#why)
    *   [Main Features](#main-features)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Contributing](#contributing)
*   [License](#license)

## About

### Why?

While the C# console is rarely used for full applications, it's often the starting point for many developers — and there's a certain charm to its simplicity that's worth preserving.  
This project aims to improve that simplicity while adding useful functionality.

### Main Features

*   **Write Batching:**  

    Reduces the overhead of multiple Console Write calls by batching them into as few operations as possible.  
    This can significantly improve performance in output-heavy scenarios.

    For more details view the [Usage](#usage) section.

*   **Command System:**  

    Inspired loosely by HTML-style syntax, allowing you to embed commands directly into strings. Example:  
    ```cs
    AConsole.WriteLine("Hello <color:red>World</color>!");
    ```  
    The command system is fully modular — you can easily extend it with custom commands for styling or any other behavior.

    For more details view the [Usage](#usage) section.

## Installation

*WIP*

## Usage

*WIP*

## Contributing

Feel free to help! [Open an issue](https://github.com/NineOfGaming/AdvancedConsole/issues/new) or submit PRs.

### Contributors
Thanks to all the people who contribute.

<a href="https://github.com/NineOfGaming/AdvancedConsole/graphs/contributors">
<img src="https://contrib.rocks/image?repo=NineOfGaming/AdvancedConsole" />
</a>

## License

This project is licensed under the GNU General Public License v3.0 - see the <a href="./LICENSE">LICENSE</a> file for details.
