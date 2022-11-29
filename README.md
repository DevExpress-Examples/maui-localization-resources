<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/571952900/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1130536)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# DevExpress .NET MAUI Controls - Localization Resources

This repository contains localization resource files with the UI strings that are translated into the following languages:

* [English (default language)](DevExpressMaui.resx)
* [German](DevExpressMaui.de.resx)
* [French](DevExpressMaui.fr.resx)

## Create a Language Resource

To localize the DevExpress .NET MAUI Controls in your application control to a language, follow the steps below:

1. Create a new resource file and name it `DevExpress.Maui.<culture_name>.resx`. The `<culture_name>` should match a language's name in the [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) standard. For example, the `DevExpress.Maui.it.resx` file is applied to your application if the device's language is **Italian**.
1. Add the created resource to your application.
1. Make sure that the `.UseDevExpress` method's parameter is set to `true`. Refer to the [Localization topic](https://docs.devexpress.devx/MAUI/404120/localization?v=22.2) for more information on how to enable an application localization.
1. **An optional step**. If you want to share your translation with the community, fork this repository, add your resource file with the translated localization strings, and create a pull request to this repository. 

## Documentation

[Localization](https://docs.devexpress.devx/MAUI/404120/localization?v=22.2)
