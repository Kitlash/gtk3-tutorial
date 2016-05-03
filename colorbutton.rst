ColorButton
===========
The ColorButton allows for the selection of a colour. The Button-like widget displays the chosen colour, and when clicked, a :doc:`colorchooserdialog` is displayed allowing the selection of the colour.

.. note::

  Internally, the ColorButton uses the :doc:`colorchooser` object to perform actions such as retrieving the selected colour. See the ColorChooser page for further methods.

===========
Constructor
===========
Construction of the ColorButton is made with::

  GtkWidget *colorbutton = gtk_color_button_new();

=======
Methods
=======
The title of the dialog launched when the ColorButton is clicked can be set via::

  gtk_color_button_set_title(GTK_COLOR_BUTTON(colorbutton), title);

=======
Example
=======
Below is an example of a ColorButton:

.. literalinclude:: _examples/colorbutton.c

Download: :download:`ColorButton <_examples/colorbutton.c>`
