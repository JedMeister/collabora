CODE (Collabora Online Development Edition) - LibreOffice Online
================================================================

LibreOffice in the Cloud on your Own Terms!

Collabora is a powerful LibreOffice-based online office that supports
all major document, spreadsheet and presentation file formats,
which you can integrate in your own infrastructure. Key features are
collaborative editing and excellent office file format support.

`Collabora Online Development Edition (CODE)`_ is intended for use by
home users and developers. Please note that this build does not provide
a "stand alone" Web UI and is intended to be integrated into third party
projects such as Nextcloud or ownCloud.

To understand the difference between CORE and LibreOffice online, please
read more here_.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- CODE (Collabora Online Development Edition) installed from Collabora
  apt repo.
- Nginx_ configured to proxy requests to the LibreOffice online daemon.
- Includes TurnKey Web Control panel with links to useful
  references and resources (convenience).
- SSL support out of the box.
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**

.. _Collabora Online Development Edition (CODE): https://www.collaboraoffice.com/code/
.. _here: https://www.collaboraoffice.com/community-en/understanding-the-differences-between-libreoffice-online-code-and-collabora-online/
.. _Nginx: https://nginx.org
.. _TurnKey Core: https://www.turnkeylinux.org/core
