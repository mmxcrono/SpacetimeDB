# Time to learn SpacetimeDB

- https://spacetimedb.com/docs/modules/c-sharp/quickstart

## Commands were run

```sh
spacetime init --lang csharp server
spacetime publish --project-path server quickstart-chat
spacetime call quickstart-chat SendMessage "Hello, World!"
spacetime logs quickstart-chat
spacetime sql quickstart-chat "SELECT * FROM Message"
```
