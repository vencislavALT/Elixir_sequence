# Sequence

Simple Sequence Server that preserves state after crash.
The architecture is as follows.
Main Supervisor
     |
     |
     |
     /\
    /  \
 Stash SubSupervisor
 Worker	   |
	   |
	Sequence
	 Worker
	 
## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `sequence` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:sequence, "~> 0.1.0"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/sequence](https://hexdocs.pm/sequence).

