Składnia elementów dokumentacji
===============================

Nagłówki
--------
Nagłówek 1
==========
Nagłówek 2
----------
Nagłówek 3
^^^^^^^^^^
Nagłówek 4
""""""""""

Akapit tekstowy
---------------
**Pogrubiony** tekst i *pochyły*.

.. note::
   To jest notatka informacyjna.

.. tip::
   To jest wskazówka.

Fragment kodu
-------------
Inline: \`print("Hello")\`

.. code-block:: python
   :linenos:

   def funkcja():
       print("Blok kodu")
       return "Wynik"

Odnośnik
--------
`Lokalny <skladnia.rst>`_
`Zewnętrzny <https://readthedocs.org>`_

Listy
-----
#. Numerowana lista
   #. Podpunkt 1
   #. Podpunkt 2

* Wypunktowana lista
  * Podpunkt z wcięciem

Termin    : Definicja terminu
Szczegóły : Dodatkowe informacje o term

Obraz
-----
.. image:: struktura.png
   :alt: Schemat struktury dokumentacji
   :width: 400px

   **Podpis pod obrazem** - opisuje co przedstawia obraz.

Tabela
------
+---------------+---------------+
| Kolumna 1     | Kolumna 2     |
+===============+===============+
| Wartość 1     | Wartość A     |
+---------------+---------------+
| Wartość 2     | Wartość B     |
+---------------+---------------+
