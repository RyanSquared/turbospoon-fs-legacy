# Turbospoon

A web framework written in FusionScript, inspired by Flask.

- What is Turbospoon?

Turbospoon is an web application development platform for FusionScript,
inspired by Flask, extending on the `lua-http` server library. It's intended to
allow for rapid application development with Turbospoon taking care of all of
the details.

- Is it production ready?

## no.

- Is there any documentation?

Not yet, but the source code is internally documented and almost all features
will have their own example to show how they work.

- What are the dependencies?

  * lua-http (`luarocks install --local http`)
    - cqueues
    - luaossl
    - basexx
    - lpeg
    - lpeg_patterns
    - fifo
  * stdlib (`fusion-pkg get stdlib` in working directory)
    - This will eventually be installable globally... Someday.. :(
