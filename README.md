# base-node-ts-project

This is a template repository that provides the essential setup for a Node.js + TypeScript project. It includes configurations for [Biome](https://biomejs.dev/) as the formatter and linter, and [Vitest](https://vitest.dev/) for testing.

---

### Features

- Pre-configured **TypeScript** environment for Node.js development.
- **Biome** for code formatting and linting.
- **Vitest** for unit and integration testing.
- Base project structure to kickstart **new applications**.
- Commonly used **scripts** already configured for development.

---

### Getting Started

1. Clone the repository or create a new project using the command below.

   ```bash
   $ git clone https://github.com/vGazzana/base-node-ts-project.git <your-project-name>
   ```

2. Navigate to the project directory:

   ```bash
   $ cd <your-project-name>
   ```

3. Install dependencies:

   > **Note**: You can use any package manager you want, here I'm using `yarn`.

   ```bash
   $ yarn install
   ```

4. Run the project in development mode:

   ```bash
   $ yarn dev
   ```

5. Build the project for production:

   ```bash
   $ yarn build
   ```

6. Start the built project:

   ```bash
   $ yarn start
   ```

---

### Pre-configured Scripts

Here are the available scripts that come pre-configured in the package.json:

- `dev`: Runs the development server with live reload using `tsx`.

  ```bash
  $ yarn dev
  ```

- `build`: Compiles the TypeScript code to JavaScript in the `./dist` folder.

  ```bash
  $ yarn build
  ```

- `start`: Runs the compiled code from the `./dist` directory.

  ```bash
  $ yarn start
  ```

- `test`: Runs the tests using Vitest.

  ```bash
  $ yarn test
  ```

- `lint`: Lints and fixes the code in the `./src` directory using Biome.

  ```bash
  $ yarn lint
  ```

- `format`: Formats the code in the `./src` directory using Biome. To write the changes, run the code below with `--write` flag.

  ```bash
  $ yarn format
  ```
