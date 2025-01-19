# Elixir List Modification Bug

This repository demonstrates a common mistake in Elixir when attempting to modify a list while iterating with `Enum.each`. The code aims to remove the element '3' from the list, but it fails to do so correctly because `Enum.each` doesn't support direct list manipulation within the iteration.  The provided solution demonstrates a more idiomatic approach.
