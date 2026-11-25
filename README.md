# Tarea UT1. Kit del técnico y documentación de DevNova

Alumno: Álvaro Márquez-Villarejo Condés. Puesto asignado: Administración y facturación (inicial M). Fuentes consultadas el 25/11/2026.

Contenido de este repositorio: este README (inventario de software, licencias aplicadas, kit de utilidades y correo profesional) y la carpeta `normas/` con el documento Normas de uso de la IA generativa en DevNova en formato editable (DOCX y ODT) y en PDF.

## Apartado 2. Inventario de software del puesto Administración y facturación (consulta 25/11/2026)
| Aplicación | Para qué la usa el puesto | Tipo | Propósito | Licencia | Modelo y coste | Alternativa (licencia distinta) |
|---|---|---|---|---|---|---|
| Microsoft 365 Empresa Estándar (Excel, Word, Outlook) | Hojas de facturación, cartas, correo | aplicación | general | Propietaria, suscripción | Suscripción: 12,13 € usuario/mes pagado anualmente, sin IVA (= 145,56 € usuario/año). https://www.microsoft.com/es-es/microsoft-365/business/microsoft-365-business-standard (25/11/2026) | LibreOffice |
| LibreOffice | Hojas y documentos | aplicación | general | MPL-2.0 | Gratuita. https://www.libreoffice.org/about-us/licenses/ (25/11/2026) | Microsoft 365 |
| Mozilla Thunderbird | Correo y calendario del puesto | aplicación | general | MPL-2.0 | Gratuita. https://www.mozilla.org/en-US/about/legal/terms/thunderbird/ (25/11/2026) | Outlook (Microsoft 365) |
| FacturaScripts | Facturas, clientes, albaranes | aplicación | específico | LGPL-3.0 | Software libre sin cuotas de licencia. https://facturascripts.com/publicaciones/licencia-de-facturascripts-492 (25/11/2026). Precio de la nube/soporte: no consultado | Un ERP propietario |
| AutoFirma | Firma electrónica de facturas y trámites con la administración | aplicación | específico | GPL-2.0 y EUPL-1.1 (doble licencia, cláusula 1 del LICENSE oficial) | Gratuita. https://firmaelectronica.gob.es/Home/Descargas.html (25/11/2026). Licencia: https://github.com/ctt-gob-es/clienteafirma/blob/master/license/LICENSE.txt | Firma en Adobe Acrobat Pro (propietaria, 23,99 EUR licencia/mes sin IVA, mismo enlace de la fila de PDFsam) |
| PDFsam Basic | Unir y dividir PDF de facturas | aplicación | general | AGPL-3.0 | Gratuita. https://pdfsam.org/pdfsam-basic/ ; licencia https://github.com/torakiki/pdfsam/blob/HEAD/LICENSE (25/11/2026) | Adobe Acrobat Pro para equipos (propietaria, suscripción): 23,99 EUR licencia/mes sin IVA. https://www.adobe.com/es/acrobat/business/pricing-plans.html (25/11/2026) |


## Apartado 3. Licencias aplicadas a LibreOffice (libre) y Microsoft 365 (propietaria)
Base: licencia MPL-2.0 de LibreOffice (https://www.libreoffice.org/about-us/licenses/) y suscripción Microsoft 365 Empresa Estándar (precio en el inventario). Correspondencia de fuentes de Microsoft: el precio de 12,13 EUR es el de la página comercial de Microsoft 365 Empresa Estándar. Para el canal comercial (por usuario) la regla de instalación está en la guía oficial de licencias https://www.microsoft.com/licensing/guidance/Microsoft-365-apps: cada usuario con licencia puede instalar y usar las aplicaciones de escritorio en hasta cinco entornos a la vez (ver también la FAQ de la página del producto, hasta cinco equipos, cinco tabletas y cinco móviles). Los Microsoft License Terms que cito después son el suplemento del canal de pequeña empresa (retail) del mismo producto, y coinciden en el límite de cinco dispositivos. Cláusula de Microsoft leída el 25/11/2026 en los Microsoft License Terms de Microsoft 365 Business Standard (https://www.microsoft.com/content/dam/microsoft/usetm/documents/microsoft-365/microsoft-365-business-standard/retail-packaged/Useterms_Retail_Microsoft365_Microsoft365BusinessStandard_Spanish.pdf, última actualización junio 2021), apartado 1.a: derecho a instalar y ejecutar copias del Servicio en hasta cinco dispositivos para uso personal y comercial; es una licencia, no una venta. 1.c: solo una persona a la vez por dispositivo, y se prohíbe instalarlo en un servidor o alojarlo comercialmente.
- Instalar en los 7 equipos: LibreOffice, sí, sin coste de licencia (MPL-2.0 permite usar y copiar). Microsoft 365: una suscripción por usuario (7 x 145,56 EUR/año sin IVA = 1.018,92 EUR/año), apartado 1.a de los términos (hasta 5 dispositivos por usuario).
- Incluirla o distribuirla a un cliente: LibreOffice, sí, cumpliendo MPL-2.0 (aviso de licencia y código de los archivos MPL modificados). Microsoft 365: no, es una licencia (no una venta) concedida al suscriptor y a los usuarios que invita (1.a); no se redistribuye a un cliente.
- Modificar y vender: LibreOffice, sí; los archivos MPL modificados siguen bajo MPL y se publica su código. Microsoft 365: no se concede ningún derecho a modificar y revender el software; solo el derecho de uso del apartado 1.a.
- Imagen CC elegida (Wikimedia Commons), guardada como img/seattle_city_light_oficina_1954.jpg (960x771, miniatura oficial de Commons):
  ![Trabajador de City Light de Seattle junto a una máquina contable IBM en una oficina en 1954](img/seattle_city_light_oficina_1954.jpg)
  Atribución TALF: "Seattle City Light worker with office machine, 1954" (Título), de Seattle Municipal Archives (Autor), licencia CC BY 2.0 https://creativecommons.org/licenses/by/2.0 (Licencia), fuente https://commons.wikimedia.org/wiki/File:Seattle_City_Light_worker_with_office_machine,_1954.jpg (Fuente). Sin cambios salvo el tamaño.
  Condiciones: BY = hay que dar atribución; no tiene SA, NC ni ND, así que permite uso comercial y modificaciones sin imponer la misma licencia. DevNova podría usarla en un folleto publicitario poniendo la atribución completa (título, autor, licencia con enlace, fuente) e indicando si se modificó.

## Apartado 4.1. Kit de utilidades (licencias comprobadas el 25/11/2026)
| Categoría | Windows | Linux |
|---|---|---|
| Antivirus | Microsoft Defender Antivirus (propietaria, incluido en Windows 11) https://www.microsoft.com/es-es/windows/comprehensive-security | ClamAV (GPL-2.0, https://docs.clamav.net/Introduction.html ; texto https://github.com/Cisco-Talos/clamav/blob/main/COPYING.txt) |
| Recuperación de datos | Recuva (propietaria; versión gratuita y Professional 24,95 EUR) https://www.ccleaner.com/recuva/update | TestDisk/PhotoRec (GPL-2.0+) https://www.cgsecurity.org/wiki/TestDisk |
| Diagnóstico de hardware | HWiNFO (propietaria; gratuita solo para uso personal y no comercial, Pro para empresas) https://www.hwinfo.com/licenses/ | inxi (GPL-3.0) https://github.com/smxi/inxi |
| Compresión | 7-Zip (LGPL con parte unRAR y BSD, https://www.7-zip.org/license.txt) | gzip (GPL, https://directory.fsf.org/project/gzip/ ; web oficial https://www.gnu.org/software/gzip/) |
| Contraseñas | KeePassXC (GPL-2.0 o GPL-3.0 según su repositorio, https://github.com/keepassxreboot/keepassxc/blob/HEAD/COPYING) | KeePassXC (mismo) |
Nota: HWiNFO es gratuito solo en entorno no comercial; en la empresa ficticia DevNova habría que usar la licencia Pro o otra herramienta (inxi, CPU-Z...). Hay que decirlo en el README.

## Apartado 5. Correo profesional con el documento de normas
Para: plantilla@devnova.example (lista interna de las 7 personas)
CC: asesoria-proteccion-datos@devnova.example
CCO: (vacío; son personas internas y no hace falta ocultar a nadie)
Asunto: Normas de uso de la IA generativa en DevNova (versión 1.0)
Cuerpo:
  Hola a todos,
  Os comparto las normas de uso de la IA generativa en DevNova. Son dos páginas y explican para qué podemos usarla, qué información no podemos introducir nunca, cómo comprobamos lo que genera y cómo lo declaramos en la documentación.
  Leedlas esta semana y escribidme si algo no queda claro. Desde el lunes se aplican a todo el trabajo de la empresa.
  Un saludo,
Firma: Álvaro Márquez-Villarejo Condés · Administración y facturación · DevNova S.L.
Adjunto o enlace: enlace a la carpeta compartida de la empresa, con permiso de solo lectura. Así todos ven la versión vigente y no circulan copias antiguas; el documento no contiene datos sensibles, así que el adjunto también sería válido.
(Direcciones de la empresa ficticia del enunciado.)

## Fuentes
Las fuentes están enlazadas en cada apartado, con la fecha de consulta.

## Uso de inteligencia artificial
He utilizado un asistente de IA para preparar textos, contrastar fuentes y dar formato.
