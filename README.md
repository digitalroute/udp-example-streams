# Pre configured streams for Usage Data Platform by DigitalRoute

Here you will find a number of example streams of various complexity that you can import into your Usage Data Platform account.

## Contributing

If you want to add/update a demo stream, feel free to create a PR!

Things to consider:
- Folder name needs to be the same as the stream file name
- A `README` file needs to be created and should contain a difficulty level and a short description of the stream
- The difficulty levels are either `Beginner`, `Intermediate` or `Advanced`

## Example
You want to add your new demo stream called "My Cool Stream".

1. Create a branch from `master`
2. Export your stream in Usage Data Platform
3. Add a directory called `my-cool-stream`
4. Create `my-cool-stream.json` in the `my-cool-stream` directory and paste your exported stream
5. Strip out everything except the `schemaVersion`, `name`, `nodes` and `edges` on the top level
6. Create a `README` in the `my-cool-stream` directory containing a difficulty level and a description
7. Create your PR towards the `master` branch