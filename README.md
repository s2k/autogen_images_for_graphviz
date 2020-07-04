# Autogenerate Images For Graphviz Using Guard

Well, automatically generate image files from GraphViz files

An example `GraphViz` file and a `Guardfile` to get started using Guard to autogenerate image files from textual graph descriptions.

Note: If you're not using a Mac you may have to remove the part `&& open #{png_file}` from the `Guardfile`, so that the command runs without an error.
