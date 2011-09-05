Stabilne API Symfony2
=======================

Stabilne API Symfony2 jest podzbiorem wszystkich publicznych metod (komponentów oraz korowych bundli)
w których możesz mieć pewność że:

* Przestrzenie nazw oraz nazwy klas się nie zmienią;
* Nazwy metod się nie zmienią;
* Deklaracja metody (argumenty oraz zwracana wartość) się nie zmieni;
* Działanie metody się nie zmieni.

Sama implementacja może się zmienić. Jedyną podstawą do zmiany stabilnego API jest bład w 
kwestii bezpieczeństwa.

Stabilne API bazuje na białej liście, otagowej tagiem `@api`. Dlatego też
wszystko nie oznaczone tagiem nie jest częścią stabilnego API.

.. tip::

    Każde zewnętrzne bundle powinny także udostępniać swoje stabilne API.

Od Symfony 2.0, komponenty poniżej posiadają swoje publiczne API:

* BrowserKit
* ClassLoader
* Console
* CssSelector
* DependencyInjection
* DomCrawler
* EventDispatcher
* Finder
* HttpFoundation
* HttpKernel
* Locale
* Process
* Routing
* Templating
* Translation
* Validator
* Yaml
