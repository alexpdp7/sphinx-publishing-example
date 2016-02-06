Graphs with Graphviz
====================

We can also create high-quality graphs with `Graphviz <http://www.graphviz.org/>`_.

.. graphviz::

   digraph foo {
      "bar" -> "baz";
   }

.. graph:: foo

   "bar" -- "baz";

.. digraph:: foo

   "bar" -> "baz" -> "quux";

To generate the graphs correctly, you will need the `dot` executable in your path. On Debian, this can be achieved by installing the `graphviz` package.
