# St-Augustine-CHS-New-Backend

The official St Augustine CHS Flutter Backend

## Getting Started

Please view this doc for guidelines on how to get started and resource links:
https://docs.google.com/document/d/1xI_6Y7_AyuUj99lc-6ZNNueimvbUyB82yg4f2qUJF_o/edit?usp=sharing

## Linting

To fix linting issues automatically:

- Use VSCode's built in tooltips

## To Serve

To serve the code on localhost, run:

- `npm run build`
- `npm run serve`

Note that serve should automatically run build, but it's finicky.

Note, to use the production database, run:

- `npm run serve:prod`

Be extremely careful when doing this! Avoid running any POST functions when doing this.

## Development

Visit `http://localhost:4000/` to view the Emulator UI. Any functions you run will only affect the emulator.

## To Deploy

To deploy the code, run: `firebase deploy --only functions`

## Pushing Code

Note that the main branch is protected, please branch off main to get started.
When making your PR, the title of your PR should follow the conventional commit template:
https://www.conventionalcommits.org/en/v1.0.0/#summary
