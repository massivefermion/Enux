# Enux

A package for reading environmental variables from env and json style configuration files and injecting them into your application.
you can also validate and document your environment.

## Installation

The package can be installed by adding `enux` to your list of dependencies in `mix.exs`:

```elixir
defp deps do
  [
    {:enux, "~> 0.9.9"},

    # if you want to load json files, you should have either this
    {:jason, "~> 1.2"},
    # or this
    {:poison, "~> 5.0"},
    # or this
    {:jaxon, "~> 2.0"}
  ]
end
```

Documentation can be found at [https://hexdocs.pm/enux](https://hexdocs.pm/enux).
