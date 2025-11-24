<a href="https://desktop.github.com?ref_product=desktop&ref_type=engagement&ref_style=button" target="_blank" class="btn btn-primary mt-3 mr-3 no-underline"><span>Download Github Desktop</span> {% octicon "link-external" height:16 aria-label="link-external" %}</a>

## About Github Desktop installation

You can install Github Desktop on supported operating systems, which currently include {% data variables.desktop.mac-osx-versions %} and {% data variables.desktop.windows-versions %}. If you have a {% data variables.product.prodname_dotcom %} or {% data variables.product.prodname_enterprise %} account, you can connect your account to Github Desktop.{% ifversion fpt or ghec %} For more information about creating an account, see [AUTOTITLE](/get-started/start-your-journey/creating-an-account-on-github).{% endif %}{% ifversion ghec %} If you're part of an organization that uses {% data variables.product.prodname_emus %} and you do not have an account, contact your enterprise administrator.{% elsif ghes %} If you're a member of an organization that uses {% data variables.product.prodname_ghe_server %} and you do not have an account, contact your site administrator.{% endif %}

{% windows %}

If you are a network administrator, you can deploy Github Desktop to computers running Windows on an Active Directory-managed network by using the Windows Installer package file (`.msi`) with Group Policy or another remote installation system.

The Windows Installer package extracts the standalone installer (`.exe`) and configures Windows to install Github Desktop the next time a user signs in to their workstation. Users must have permissions to install Github Desktop in their user directory.

If a user runs the Windows Installer package for Github Desktop directly, to complete the installation, the user must sign out of their workstation and then sign back in.

{% endwindows %}

## Downloading and installing Github Desktop

{% mac %}

You can install Github Desktop on {% data variables.desktop.mac-osx-versions %}.

{% data reusables.desktop.download-desktop-page %}
1. Click **Download for macOS**.
1. In your computer's `Downloads` folder, double-click the **Github Desktop** zip file.
1. After the file has been unzipped, double-click the **Github Desktop** application file.
1. Github Desktop will launch after installation is complete.

{% endmac %}

{% windows %}

You can install Github Desktop on {% data variables.desktop.windows-versions %}.

> [!WARNING]
> You must have a 64-bit operating system to run Github Desktop.

{% data reusables.desktop.download-desktop-page %}
1. Click **Download for Windows**.
1. In your computer's `Downloads` folder, double-click the **Github Desktop** setup file.
1. Github Desktop will launch after installation is complete.

{% endwindows %}

{% linux %}

Linux is not yet supported

{% endlinux %}
