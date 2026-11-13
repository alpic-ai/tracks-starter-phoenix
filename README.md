# Phoenix starter

A minimal Phoenix app in Elixir with LiveView, Tailwind CSS and esbuild, and no database.

- `lib/app_web/router.ex`: the routes
- `lib/app_web/controllers/page_controller.ex`: the home page's controller
- `lib/app_web/controllers/page_html/home.html.heex`: the home page
- `lib/app_web/components/layouts.ex`: the layout around it
- `assets/`: its CSS and JavaScript

## Run

```sh
mix setup
mix phx.server
```

Then open http://localhost:4000.
