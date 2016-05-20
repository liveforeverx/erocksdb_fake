# Erocksdb

Fake app for replacement of erocksdb, if it is specified as dependency, but not needed.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add erocksdb to your list of dependencies in `mix.exs`:

        def deps do
          [{:erocksdb, "~> 0.0.1"}]
        end

  2. Ensure erocksdb is started before your application:

        def application do
          [applications: [:erocksdb]]
        end

