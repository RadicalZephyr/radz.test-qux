# Dependency Diamond

These repositories display the classic conflicting versions dependency
diamond.

foo 1.0 depends on bar 1.0 and baz 1.0, both of which depend on qux
1.0

foo 2.0 depends on bar 1.0 and baz 2.0 which updates its qux version
to 2.0.

Thus foo 2.0 has a transitive dependency on qux 1.0 and qux 2.0,
through bar and baz respectively.
