# 🤖 Proyecto de Automatizacion QA - Damian Azar Hidalgo
Proyecto final de automatización QA Talento Lab

## Descripcion del trabajo

Proyecto final del curso de Automatizacion QA realizado con Python, Selenium WebDriver y Pytest.

El objetivo de este proyecto es conseguir automatizar distintas pruebas funcionales de una aplicacion web.

## Elementos usados

* Lenguaje: Python
* Automatización: Selenium WebDriver
* Framework para Testing: Pytest
* Pruebas de API: Requests
* Reportes: Pytest-html (con screenshots ante fallos)
* Control de versiones: Git y GitHub

## ¿Cómo proceder con la instalación?

`git clone https://github.com/damian-azarh/proyecto-final-automation-testing--Damian-Azar-Hidalgo-`

## ¿Cómo instalar dependencias?

`pip install -r requirements.txt`

## ¿Cómo ejecutar las pruebas?

Para ejecutar las pruebas con el reporte correspondiente, se utiliza el siguiente comando:

`pytest --html=reports/report.html`

## ¿Cómo es el funcionamiento de las pruebas?

**Test Login:** Se valida el acceso exitoso al sitio y se manejan los errores que puedan surgir con archivos CSV.

**Test Inventory:** Se verifica la carga correcta de los productos y se navega la pagina del inventario. 

**Test Cart:** Se hacen pruebas funcionales del carrito, incluyendo añadir objetos, eliminar objetos, verificar los items en el carrito y parametrizacion con archivos JSON.

**Test API:** Se validan metodos HTTP en endpoints publicos ademas de la integridad de los datos que devuelven las respuestas JSON.
