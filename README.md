# Glitchcrafter React Extension Pack 

Reclaim Your Time with Glitchcrafter React Extension Pack for VS Code: The Essential Toolkit, Pre-Assembled.

Accelerate your React development workflow by eliminating the time-consuming task of individually installing essential extensions. Glitchcrafter delivers a fully equipped environment, ready to boost your productivity in a new VS Code setup.

Simplify your VS Code profile management and avoid the oversight of missing critical tools. Our expertly curated extension pack for React development guarantees you have everything you need from the start.

Invest your valuable time in development, innovation, and creative problem-solving, not in wrestling with initial configuration roadblocks when starting new React projects in VS Code.

Say goodbye to the risk of forgetting vital development extensions. In contrast to manual setup, with Glitchcrafter, accessing a comprehensive set of top-tier React development tools is as simple as installing a single extension.

> **Note**: I recommend to use this extension pack in a new profile and restart VSCode after installation to ensure all extensions are working correctly.

## Table of Contents

- [Glitchcrafter React Extension Pack](#glitchcrafter-react-extension-pack)
  - [Table of Contents](#table-of-contents)
  - [Included Extensions](#included-extensions)
    - [ES7+ React/Redux/React-Native Snippets](#es7-reactreduxreact-native-snippets)
    - [CSS Peek](#css-peek)
    - [Stylelint](#stylelint)
    - [Autoprefixer](#autoprefixer)
    - [JavaScript/TypeScript Postfix Completion](#javascripttypescript-postfix-completion)
    - [ESLint](#eslint)
    - [Prettier - Code formatter](#prettier---code-formatter)
    - [Error Lens](#error-lens)
    - [IntelliSense for CSS class names in HTML](#intellisense-for-css-class-names-in-html)
    - [i18n Ally](#i18n-ally)
    - [Markdown All in One](#markdown-all-in-one)
    - [gi](#gi)
    - [GitLink](#gitlink)
    - [Import Cost](#import-cost)
    - [Npm Intellisense](#npm-intellisense)
    - [Parameter Hints - Instant Function Argument Clarity](#parameter-hints---instant-function-argument-clarity)
    - [Paste JSON as Code - Instantly Generate Robust Types and Serialization Code](#paste-json-as-code---instantly-generate-robust-types-and-serialization-code)
    - [TypeScript Destructure Plugin - Simplify Your Object Handling](#typescript-destructure-plugin---simplify-your-object-handling)
    - [Better Comments](#better-comments)
    - [Auto Close Tag](#auto-close-tag)
    - [Auto Rename Tag](#auto-rename-tag)
    - [React Hooks Snippets](#react-hooks-snippets)
    - [VSCode React Refactor](#vscode-react-refactor)
    - [GitLens — Git supercharged](#gitlens--git-supercharged)
  - [Changes](#changes)
    - [Version 0.0.1](#version-001)
    - [Version 0.0.2](#version-002)



## Included Extensions


### ES7+ React/Redux/React-Native Snippets

**Author: dsznajder**

Dramatically accelerate your React, Redux, and React Native development with this comprehensive collection of ES7+ code snippets. Designed with TypeScript support, this extension streamlines component creation by allowing you to generate boilerplate code with simple, intuitive shortcuts.

Stop manually initializing new React component files. With this extension, a few keystrokes will instantly scaffold common patterns and structures, freeing you to focus on the core logic and functionality of your application.

**Key Features:**

* **Rapid Component Creation:**  Generate common component structures and patterns in seconds.
* **TypeScript Support:**  Seamlessly integrates with TypeScript projects for type-safe development.
* **Boosted Productivity:**  Eliminate repetitive typing and boilerplate code.
* **Consistent Code Style:**  Enforce consistent coding conventions across your project.

**Additional Information**

[ES7+ React/Redux/React-Native snippet list](https://github.com/r5n-labs/vscode-react-javascript-snippets/blob/master/docs/Snippets.md)

### CSS Peek

**Author: Pranay Prakash**

Dramatically enhance your VS Code workflow with CSS Peek, the extension that lets you jump directly to CSS, SASS, or Less declarations from your HTML. Simply hover over the HTML property (class, ID, etc.) to preview the corresponding style code, or use "Go to Definition" to navigate directly to the stylesheet.

Inspired by the popular "CSS Inline Editors" feature in Brackets, CSS Peek brings that time-saving functionality to Visual Studio Code, offering the best of both worlds for rapid CSS editing and code navigation.

**Key Features:**

* **Accelerated CSS Editing:**  Quickly access and modify CSS rules without leaving your HTML file.
* **Intuitive Navigation:** Jump to CSS definitions directly from HTML class and ID names.
* **Instant Style Preview:** Hover over HTML attributes to see the relevant CSS styles.
* **Enhanced Productivity:** Streamline your front-end development workflow.

**Additional Information**


[CSS Peek Main Repository](https://github.com/pranaygp/vscode-css-peek)


### Stylelint
**Author: Stylelint.io**

Leverage the power of Stylelint directly within your VS Code editor to maintain consistent code styles and catch errors in your stylesheets. This extension provides real-time feedback, helping you write cleaner and more maintainable CSS, SCSS, Less, and other PostCSS syntaxes.

**Key Features:**

* **Real-time Linting:**  Stylelint analyzes your CSS and PostCSS files as you type, highlighting potential issues directly in the editor.
* **Highly Configurable:** Customize linting rules to match your project's specific style guidelines using a Stylelint configuration file.
* **Supports Multiple Syntaxes:**  Validate CSS, PostCSS, SCSS, Less, and other syntaxes with appropriate configuration.
* **Workspace and Global Installation:** Detects Stylelint installations within your project or globally on your machine.
* **Error and Warning Display:**  Clearly displays Stylelint errors and warnings in the VS Code Problems panel.

**Additional Information**


[StyleLint official Repository](https://github.com/stylelint/vscode-stylelint)

### Autoprefixer
**Author: mrmlnc**


Autoprefixer is a powerful PostCSS plugin that automatically adds [vendor prefixes](https://developer.mozilla.org/en-US/docs/Glossary/Vendor_Prefix) (--webkit, --moz, -o- -ms-) to your CSS rules, ensuring **cross-browser compatibility without manual prefix management**. It uses data from "Can I Use" to apply only the necessary prefixes based on current browser popularity and feature support.

**Key Features:**

* **Automatic Prefixing:**  Adds necessary vendor prefixes to CSS properties based on browser support.
* **Browserslist Integration:**  Uses Browserslist to target specific browser versions and market share.
* **Simplifies CSS Authoring:** Write clean, unprefixed CSS and let Autoprefixer handle the vendor prefixes.
* **Recommended by Industry Leaders:** Used and recommended by Google, Twitter, and Alibaba.
* **Grid Layout Polyfill (Optional):**  Can translate modern CSS Grid syntax for IE 10 & 11 (requires explicit configuration and testing).
* **Removes Outdated Prefixes:** Can be configured to remove unnecessary prefixes.
* **Integration with Build Tools:** Works seamlessly with Gulp, Webpack, and other build systems.
* **Control Comments:**  Allows you to selectively enable or disable Autoprefixer for specific CSS blocks.

**Additional Information**


[AutoPrefixer official Github Repository](https://github.com/mrmlnc/vscode-autoprefixer).

### JavaScript/TypeScript Postfix Completion

**Author: Ireneusz Patalas**

Boost your JavaScript and TypeScript coding speed with postfix templates! This extension, inspired by ReSharper, reduces repetitive cursor movements by allowing you to apply common code transformations directly from an expression. Write your code fluently and let postfix completion handle the boilerplate.

**Key Features:**

* **Postfix Templates:** Apply code transformations like `if`, `for`, `console.log`, and more, directly to an expression.
* **Increased Productivity:** Minimize cursor jumping and streamline common coding patterns.
* **Supports JavaScript and TypeScript:** Works seamlessly in both JavaScript and TypeScript projects.
* **Multiline Expression Support:**  Apply templates to complex, multiline expressions.
* **Customizable Templates:** Add your own custom postfix templates to suit your specific needs.
* **Variable Name Inference:**  Suggests intelligent variable names for `var`, `let`, `const`, `for...of`, and `forEach` statements.
* **Disable Built-in Templates:**  Disable specific built-in templates you don't use or prefer not to see.
* **Language Configuration:**  Enable the extension in specific languages, including inline JS/TS in HTML and Vue files.

**Additional Information**

[PostFix TS Extension Official Repository](https://github.com/ipatalas/vscode-postfix-ts)

### ESLint

**Author: Microsoft**

The VS Code ESLint extension seamlessly integrates the ESLint JavaScript linter directly into your Visual Studio Code editor. It provides real-time feedback on your code, helping you identify and fix stylistic issues and potential errors as you write.

> **Note**: For this extension to Work you need to install the [NPM package for ESLint](https://www.npmjs.com/package/eslint) to work [Click here for more information](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint#eslint-6x).

**Key Features:**

* **Integrated ESLint:** Runs ESLint within VS Code for immediate feedback.
* **Workspace and Global ESLint Support:** Uses the ESLint library installed in your project or a globally installed version.
* **Real-time Error Detection:**  Highlights linting errors and warnings directly in your code.
* **Configuration Assistance:** Provides commands to create ESLint configuration files (`.eslintrc`).
* **Supports TypeScript:** Can be configured to lint TypeScript files.

**Aditional Information**

[EsLint Official Documentation](https://eslint.org/docs/latest/use/command-line-interface)

[EsLint VSCode Extension official page](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint#eslint-6x)

### Prettier - Code formatter

**Author: Prettier**

Prettier is an opinionated code formatter for Visual Studio Code that **ensures consistent code style across your project**. It automatically parses your code and re-prints it according to its own set of rules, handling line wrapping and other formatting details.

**Key Features:**

* **Opinionated Formatting:** Enforces a consistent code style automatically.
* **Supports Multiple Languages:**  Formats JavaScript, TypeScript, CSS, SCSS, Less, HTML, Vue, Angular, GraphQL, Markdown, YAML, and more.
* **Easy to Install and Use:** Simple installation through VS Code extensions.
* **Local and Global Prettier Resolution:** Can use Prettier versions installed in your project or globally.
* **Plugin Support:** Extends functionality with support for Prettier plugins.
* **Configurable via Files or Settings:** Customize Prettier's behavior using configuration files (`.prettierrc`, `.editorconfig`) or VS Code settings.
* **Format on Save:** Automatically formats code when you save a file.
* **Format Selection:** Allows you to format only a selected portion of your code.
* **Linter Integration:** Works well with linters by handling formatting concerns.

**Additional Information**

[Prettier Official Repository](https://github.com/prettier/prettier-vscode)

[Prettier Official Documentation](https://prettier.io/docs/en/)


### Error Lens
**Author : Alexander**

Error Lens **significantly enhances the visibility of language diagnostics in VS Code** by highlighting entire lines, appending messages inline, and displaying icons in the gutter, making errors and warnings immediately apparent.

**Key Features:**

* **Line Highlighting:**  Highlights the entire line containing errors, warnings, info, or hints.
* **Inline Message Display:** Appends the diagnostic message directly to the end of the affected line.
* **Gutter Icons:** Shows error, warning, info, and hint icons in the editor gutter.
* **Status Bar Integration:** Optionally displays error and warning counts, or the active line's diagnostic message, in the status bar.
* **Customizable Display:** Offers numerous settings to customize the appearance and behavior of the diagnostic indicators.


**Additional Information**

[Error Lens Official Repository](https://github.com/usernamehw/vscode-error-lens)


### IntelliSense for CSS class names in HTML

**Author: Zignd**

This Visual Studio Code extension enhances your HTML coding experience by providing intelligent autocompletion for CSS class names. It scans your workspace for CSS definitions (in CSS, SCSS, Less files, and styles within supported file types) and suggests matching class names as you type the `class` attribute in your HTML. It also supports external stylesheets linked in your HTML.

**Key Features:**

* **CSS Class Autocompletion:**  Provides suggestions for CSS class names within HTML `class` attributes.
* **Workspace-Wide Scanning:**  Identifies CSS definitions across your entire project.
* **External Stylesheet Support:**  Includes class names from linked CSS files.
* **Manual Cache Refresh:**  Allows you to manually trigger a re-scan for new or updated CSS classes.
* **Customizable File Inclusion/Exclusion:**  Provides settings to control which folders and files are scanned for CSS definitions.
* **Support for Multiple Languages:** Works with HTML, Razor, PHP, Laravel (Blade), JavaScript, React, Vue, Twig, Markdown, and more.
* **"@apply" Directive Support:** Offers specific support for the `@apply` directive in CSS preprocessors (Tailwind CSS).
* **Emmet Integration (Optional):**  Triggers autocompletion for Emmet abbreviations starting with ".".


**Additional Information**

[IntelliSense for CSS class names in HTML Official Repository](https://github.com/Zignd/HTML-CSS-Class-Completion)


### i18n Ally

**Author: Lokalise**

i18n Ally is a powerful Visual Studio Code extension designed to streamline the internationalization (i18n) workflow for developers. It provides comprehensive tools for managing translations directly within your editor, enhancing productivity and collaboration.

**Key Features:**

* **Inline Annotations:** Displays translations directly within your code.
* **Hover and Direct Actions:**  Offers quick access to translation details and actions on hover.
* **Centralized Translation Management:** Provides a dedicated editor UI to manage all your translations in one place.
* **Review System:** Facilitates the review and validation of translations.
* **Code Extraction:** Automatically extracts translatable strings from your codebase.
* **Missing Translation Reports:** Identifies and reports missing translations.
* **Machine Translation Integration:** Offers access to machine translation services.
* **JSON and YAML Annotation:** Provides specific support for JSON and YAML translation files.
* **Multi-Framework Support:** Works with numerous popular JavaScript frameworks.
* **Linked Locale Message Support:**  Handles complex translation structures with linked messages.

**Additional Information**

[I18nAlly official repository](https://github.com/lokalise/i18n-ally)

### Markdown All in One

**Author: Yu Zhang**

This extension provides a **comprehensive suite of tools to enhance your Markdown editing experience in Visual Studio Code**. It offers keyboard shortcuts, table of contents generation and updating, list editing enhancements, and more, making working with Markdown documents more efficient.

**Key Features:**

* **Keyboard Shortcuts:** Provides shortcuts for common Markdown formatting tasks (bold, italic, lists, etc.).
* **Table of Contents Generation:**  Easily create and automatically update tables of contents.
* **Enhanced List Editing:**  Improves list creation and manipulation with features like auto-numbering and indentation correction.
* **Print to HTML:**  Allows you to export your Markdown documents to HTML.
* **GitHub Flavored Markdown Support:**  Includes support for GFM features like table formatting and task lists.
* **Math Rendering:** Supports rendering mathematical formulas using KaTeX (can be disabled if using a dedicated math extension).
* **Auto Completions:** Offers suggestions for images, file paths, math functions, and reference links.

**Additional Information**

[Markdown All in One Official Repository](https://github.com/yzhang-gh/vscode-markdown)

### gi

**Author: Hasit Mistry**

gi is a Visual Studio Code extension that simplifies the creation of `.gitignore` files. It leverages the gitignore.io API to provide an up-to-date list of operating systems, IDEs, and programming languages, allowing you to quickly generate comprehensive `.gitignore` files for your projects.

**Key Features:**

* **Easy `.gitignore` Generation:**  Create `.gitignore` files directly from within VS Code.
* **gitignore.io Integration:** Uses the popular gitignore.io API for an extensive and current list of templates.
* **Quick Search:**  Allows you to search for specific operating systems, IDEs, and programming languages to include in your `.gitignore`.
* **Command Palette Access:** Easily accessible through the VS Code command palette.
* **Informative Feedback:** Provides status updates and confirmation messages during the `.gitignore` creation process.

**Additional Information**
[gi Official Repository](https://github.com/hasit/vscode-gi)


### GitLink

**Author: Qinen Zhu**

GitLink streamlines collaboration by making it incredibly easy to share direct links to your code files on platforms like GitHub, GitLab, BitBucket, and Azure DevOps. Quickly navigate to the online version of the current file in your browser or copy the link to your clipboard for seamless sharing with your team.

**Key Features:**

* **Effortless Link Sharing:** Instantly generate and share URLs to the online version of your currently open file.
* **Direct Browser Access:** Quickly open the current file in your web browser on your Git hosting platform.
* **Copy to Clipboard:**  Copy the online file link to your clipboard for easy pasting into messages, emails, or documentation.
* **Multi-Platform Support:** Compatible with popular Git hosting services like GitHub, GitLab, BitBucket, and Azure DevOps.
* **Default Remote Configuration:**  Set a default remote repository to avoid repeatedly selecting from multiple remotes, further accelerating your collaborative workflow.

**Additional Information**

[GitLink Official Repository](https://github.com/qinezh/vscode-gitlink)

### Import Cost

**Author: Wix**

Effectively manage the size impact of your imports with the Import Cost VSCode extension. This tool provides immediate, inline visibility into the bundle size contributed by each imported package, helping you identify potential space complexities and optimize your application's footprint.

**Key Features:**

* **Inline Import Size Display:** Shows the calculated size of imported packages directly within the editor.
* **Supports Various Import Styles:**  Accurately calculates sizes for default, entire content, selective, aliased, and submodule imports, as well as `require` statements.
* **JavaScript and TypeScript Compatibility:** Works seamlessly with both JavaScript and TypeScript projects.
* **Identifies Potential Bloat:**  Highlights the space overhead introduced by individual imports, enabling you to make informed decisions about your dependencies.
* **Webpack Powered:**  Leverages webpack's capabilities to reliably determine import sizes.

**Additional Information**

[Import Cost Official Repository](https://github.com/wix/import-cost)


### Npm Intellisense

Npm Intellisense is a Visual Studio Code plugin that significantly accelerates your workflow by providing autocompletion for npm modules directly within your import statements. Stop manually typing out package names and quickly access the modules you need.

**Key Features:**

**Author: Christian Kohler**

* **Automatic NPM Module Completion:**  Suggests npm modules as you type import statements.
* **Supports Various Import Styles:**  Works with both ES6 `import` and CommonJS `require` syntax.
* **`devDependencies` Support (Optional):** Can be configured to include `devDependencies` in the autocompletion list.
* **Built-in Module Recognition:**  Suggests built-in Node.js modules like `path` and `fs`.
* **Recursive `package.json` Lookup:**  Finds `package.json` files in the nearest directory for accurate suggestions.
* **Experimental Subfolder Intellisense:**  Offers (experimental) autocompletion for subfolders within npm modules.

**Additional Information**

[Npm Intellisense Official Repository](https://github.com/ChristianKohler/NpmIntellisense)


### Parameter Hints - Instant Function Argument Clarity

**Author: Dominic Vonk**

Stop guessing function parameters! Parameter Hints intelligently displays the names of function arguments as you type, directly within your editor. Boost your coding efficiency and reduce errors by having parameter information readily available.

**Key Features:**
* **Effortless Parameter Recall:**  No more looking up documentation or jumping between files. See the parameter names you need, right when you need them.
* **Accelerated Development:**  Write code faster and more accurately by eliminating the need to remember parameter order and names.
* **Reduced Errors:**  Minimize the risk of passing arguments in the wrong order or with incorrect names, leading to fewer bugs and wasted debugging time.
* **Enhanced Code Understanding:**  Quickly grasp the expected inputs of functions, especially when working with unfamiliar codebases or libraries.
* **Customizable Experience:** Tailor the hints to your preferences with customizable colors, padding, and language support.

**Additional Information**

[Parameter Hints Official Repository](
https://github.com/DominicVonk/VSCode-Parameter-Hints)


### Paste JSON as Code - Instantly Generate Robust Types and Serialization Code

**Author: quicktype**

Stop hand-crafting data models! Paste JSON as Code is your intelligent coding assistant that automatically generates accurate, strongly-typed models and (de-)serialization code directly from JSON, JSON Schema, and TypeScript. Boost your productivity and ensure data integrity across a vast array of popular programming languages.

**Key Features:**
* **Effortless Type Generation:**  Simply paste or load your JSON, JSON Schema, or TypeScript, and Paste JSON as Code will instantly infer and generate corresponding types.
* **Seamless Serialization/Deserialization:**  Go beyond just types – generate the code needed to effortlessly convert data to and from your defined models.
* **Broad Language Support:**  Supports an extensive range of languages including C#, C++, Java, JavaScript, Python, TypeScript, and many more, ensuring compatibility across your projects.
* **Interactive and Intuitive:**  Easily access Paste JSON as Code's powerful features directly within your editor through simple commands like "Open Paste JSON as Code for JSON" and "Paste JSON as code/types".
* **Highly Customizable:** Fine-tune the generation process with options to control map and enum inference, date/time handling, and more, tailoring the output to your specific needs.

**Additional Information**

[Paste JSON as Code Official Repository](https://github.com/glideapps/quicktype)

### TypeScript Destructure Plugin - Simplify Your Object Handling

**Author: tusaeff**

Tired of repetitive object property access in TypeScript? The TypeScript Destructure Plugin streamlines your code by providing intelligent source actions to effortlessly create destructuring assignments, refactor function parameters, and manipulate rest operators. Boost your coding efficiency and write cleaner, more readable TypeScript.

**Key Features:**
* **Instant Destructuring:**  Quickly generate destructuring assignments for object properties with a single action, saving significant typing time.
* **Effortless Parameter Refactoring:**  Convert function parameters into destructuring patterns with ease, making your function signatures more expressive.
* **Smart Property Unfolding:**  Intelligently destructure nested object properties in one step, eliminating manual drilling down.
* **Flexible Rest Operator Management:**  Easily collapse selected properties into a rest operator variable or expand existing rest operators into individual variables.
* **Boosted Code Readability:**  Write cleaner and more concise code by leveraging the power of destructuring with minimal effort.

**Additional Information**
(TypeScript Destructure Plugin Official Repository)[https://github.com/tusaeff/vscode-typescript-destructure-plugin]

### Better Comments
**Author: Aaron Bond**

Create more human-friendly comments in your code by categorizing annotations into alerts, queries, TODOs, highlights, and custom styles.

**Key Features:**
* **Categorize Annotations:** Style comments as alerts, queries, TODOs, highlights, and more.
* **Customizable Styles:** Define your own comment styles with specific colors and formatting.
* **Commented Out Code Styling:**  Visually distinguish commented-out code.
* **Multiline Comment Support:** Choose whether to apply styles to multiline comments.
* **Plain Text Support:** Optionally style comments in plain text files.
* **Extensive Language Support:** Works with a wide range of programming languages.

**Additional Information**
(Better Comments Official Repository)[https://github.com/aaron-bond/better-comments.git]
(Better Comments Homepage)[https://github.com/aaron-bond/better-comments/blob/master/README.md]

### Auto Close Tag

**Author: Jun Han**

Automatically add HTML/XML close tags, mirroring the behavior of Visual Studio IDE and Sublime Text, and extending this functionality to languages beyond the built-in support.

**Key Features:**
- Automatically adds closing tags when typing the closing bracket of the opening tag.
- Places the cursor between the opening and closing tags after insertion.
- Allows setting a list of tags that should not be auto-closed.
- Automatically closes self-closing tags.
- Offers a Sublime Text 3 mode for adding closing tags when typing `</`.
- Provides a keyboard shortcut (`Alt+.` or `Command+Alt+.`) and Command Palette option to manually add closing tags.

**Additional Information**
[Auto Close Tag Official Repository](https://github.com/formulahendry/vscode-auto-close-tag)


### Auto Rename Tag

**Author: Jun Han**

Automatically rename paired HTML/XML tags, mirroring the functionality of Visual Studio IDE.

**Key Features:**
- Automatically renames the paired HTML/XML tag when you rename one tag.

**Additional Information**

[Auto Rename Tag Official Repository](https://github.com/formulahendry/vscode-auto-rename-tag)
[Homepage](https://github.com/formulahendry/vscode-auto-rename-tag/blob/master/README.md)

### React Hooks Snippets

**Author: Al Duncanson**
Code snippets for React Hooks to make writing them easier and faster.

**Key Features:**
- Provides snippets for common React Hooks like `useState`, `useEffect`, `useContext`, etc.
- Includes snippets for importing React and common hooks.
- Offers snippets for React Redux hooks like `useSelector` and `useDispatch`.

**Additional Information**
[React Hooks Snippets Official Repository](https://github.com/alDuncanson/react-hooks-snippets)


### VSCode React Refactor

**Author: PlanBCoding**

Recompose your overgrown JSX without worrying about the given data.

**Key Features:**
- Extract JSX code parts to a new class or functionnal component
- Supports TypeScript and TSX
- Works with classes, functions and arrow functions
- Handles key attribute and function bindings
- Compatible with React Hooks API
- Added `Extract to Class Component` Code action
- Added option to config Custom Babel plugins used by parser
- Added option to choose generated function type
- Added error message on parse error
- Updated @babel modules to the latest version

**Additional Information**
[VSCode React Refactor Official Repository](https://github.com/planbcoding/vscode-react-refactor.git)

### GitLens — Git supercharged

**Author: GitKraken**

Supercharges Git within VS Code, providing visualizations of code authorship, seamless navigation of Git repositories, and insights through rich visualizations and powerful comparison commands.

**Key Features:**
- Visualize code authorship at a glance via Git blame annotations and CodeLens.
- Seamlessly navigate and explore Git repositories.
- Gain valuable insights via rich visualizations.
- Utilize powerful comparison commands.
- Accelerate PR reviews with Launchpad (Pro).
- Manage commits effortlessly using the Commit Graph (Pro).
- Streamline collaboration with Cloud Patches and Code Suggest (Preview).

**Additional Information**
[GitLens — Git supercharged Official Repository](https://github.com/gitkraken/vscode-gitlens)
[Homepage](https://gitkraken.com/gitlens)
[GitLens Help Center](https://help.gitkraken.com/gitlens/gitlens-home/)

## Changes

### Version 0.0.1

- Initial release of Glitchcrafter React Extension Pack.

### Version 0.0.2

- Minor Changes to the README.md file.
- Added GitLens and Minor Markdown Corrections.
