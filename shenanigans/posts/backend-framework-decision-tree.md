Behold my ~~proprietary~~ completely exhaustive **Choose Your Own ~~Adventure~~ Backend Stack Decision-Assisting ~~Binary~~ tree**.

_Originally for [the node subreddit](https://www.reddit.com/r/node), thus the JS bias, but Reddit didn't let me post it, probably wisely_

1. Do you like JavaScript?
   * Yes: Go to 2.
   * No: ~~Go away~~ Go to 14.
2. Do you like *dependency injection*?
   * Yes: Go to 1 - *whoops, circular dependency! Go to 3!*
   * No: Go to 4.
3. ~~Do you have a decorator addiction~~ Do you like more freedom at the cost of structure?
   * **Yes: use Nest** & use Postgres via MikroOrm or BYO ORM/Builder e.g. Drizzle. (TypeORM is the default but it seems people have a lot of beef with it)
   * **No: use Adonis + Lucid**.
4. Do you like *living on the edge*?
   * **Yes: Go with Elysia + Turso**.
   * No: Go to 5.
5. Do you like *serving requests on the edge*?
   * **Yes: Go with Hono** \+ Durable Objects (or Postgres/Turso/etc).
   * No: Go to 6.
6. Do you like ~~lighthouse scores~~ *full-stack frameworks with hybrid rendering*?
   * Yes: Go to 7.
   * No: Go to 10.
7. Which frontend framework do you like?
   * React: Go to 8.
   * **Vue: Go with Nuxt**.
   * **Angular: Go with Analog JS**.
   * **Svelte: Go with Svelte(Kit)**.
   * **Solid: Go with SolidStart**
   * *note: for all of these leaf nodes, this means you're probably using the framework's built-in server, often Nitro/H3, but you can also easily use **Hono**, etc too*
   * *BYO DB "can do" attitude preferred*
8. Do you secretly like Preact or Deno?
   * **Yes: Go with Deno Fresh**
   * No: Go to 9.
9. Do you like Vite?
   * **Yes: Go with Remix/React-Router**
   * **No: Go with Next JS**.
10. Do you like the idea of having type-safe requests in your frontend?
   * Yes: Go to 11
   * No: Go to 12.
11. Do you *really really really* like Zod?
   * **Yes: Go with TRPC**
   * **No: Go with Hono/Elysia + Postgres (BYO ORM/Query Builder).**
12. Do you like *directory-based auto-importing magic*?
   * **Yes: Go with Nitro**.
   * No: Go to 13.
13. Do you like *generating API documentation automatically?*
   * **Yes: Go with Fastify.**
   * **No: Go with Express**.
14. Do you like *employment opportunities*?
   * Yes: Go to 15.
   * No: Go to 17.
15. Do you plan to work in a *Dotnet-town* or a *Java-town*?
   * **Dotnet-town: Go with ASP** (Postgres or SQL Server if your company prefers it)
   * **Java-town**: **Spring Boot** (Postgres or MySQL if your company prefers it)
   * No: Go to 16.
16. Do you like the whole "DIY" vibe but wish C had garbage collection?
   * **Yes: Go with Go (echo, etc)** \+ Postgres etc
   * **No: Go to with Ruby on Rails/Django/Laravel**.
17. Do you like dynamically typed languages?
   * Yes: Go to 18.
   * No: Go to 19.
18. Do you like whole "DIY" vibe but with *parentheses*?
   * Yes: **Go with Clojure** (e.g. Ring etc) + Datomic if you're brave (otherwise... Postgres)
   * No: **Go with Elixir Phoenix** \+ Postgres
19. Do you like systems programming?
   * **Yes: Go with Rust Axum.**
   * **No: Go with Gleam Wisp** *(also relevant to the Node community, Gleam can compile to JS, output .d.ts files (I think), and integrate with Vite and I think someone even got it working in Vue??)*

  
That's it. If you've reached the end, you've seen every single backend stack possible. If anyone says "Oh, I use Javalin", "I prefer Ktor", "Lua Lapis is kind of nice", "What about Koa?", "I write all my lambdas using F# and Fable for minimum cold-starts", or "didn't you just say you work with Meteor a lot?", you can now confidently respond to them with "*those are psy-ops from Big-FOSS and I will not be deceived, heathen!*", which is a great way to conduct professional networking.

In all seriousness, I still find this depends on too many factors and is very circumstancial.
