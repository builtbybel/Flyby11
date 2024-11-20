# Flyby11 (FlybyScript) Windows 11 for All – No Specs, No Problem!
Flyby11 is a simple patcher that removes the annoying restrictions preventing you from installing Windows 11 (24H2) on unsupported hardware. Got an old PC? No TPM, Secure Boot, or your processor isn't supported? Flyby11 lets you install Windows 11 24H2 anyway.
No complicated steps. Just run the tool (see "Releases" in the right side of the page, you may need to unpack a zip file), and you'll be running Windows 11 on your outdated machine in no time. Think of it as sneaking through the back door without anyone noticing.

# Technical Overview
Flyby11 leverages a feature of the Windows 11 setup process that uses the Windows Server variant of the installation. This variant, unlike the regular Windows 11 setup, skips most hardware compatibility checks, allowing it to run on unsupported systems. Here’s a more technical breakdown of the process:

Windows Server Setup: The tool uses the Windows Server variant of the setup, which avoids the usual checks for things like TPM, Secure Boot, and specific processor requirements.
Install Regular Windows 11: Even though the setup runs in server mode, it installs the normal Windows 11 version (not the server version).
Manual ISO Preparation: Flyby11 automates the download and mounting of the ISO, so you don’t need to manually tweak anything. You can get the ISO from official sources or the tool will handle it using the [Fido script](https://github.com/pbatard/Fido)
This method is the same approach described in the official Windows documentation for upgrading unsupported systems, as [detailed in this article](https://support.microsoft.com/en-us/windows/ways-to-install-windows-11-e0edbbfb-cfc5-4011-868b-2ce77ac7c70e)

_Flyby11 offers all the currently working methods to bypass the restrictions for installing Windows 11 24H2 on unsupported hardware. The internet is full of guides showing how to get around the TPM, Secure Boot, and processor requirements, but Flyby11 does all that automatically for you._
