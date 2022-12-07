<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/571952900/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1130536)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# DevExpress .NET MAUI Controls - Localization Resources

This repository contains localization resource files with UI strings translated into the following languages:

* [English (default language)](DevExpressMaui.resx)
* [German](DevExpressMaui.de.resx)
* [French](DevExpressMaui.fr.resx)

## Create a Language Resource

Follow the steps below to localize DevExpress .NET MAUI Controls to a specific language:

1. Create a new resource file and name it `DevExpress.Maui.<culture_name>.resx`. The `<culture_name>` should match language (based on the [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) standard). For example, `DevExpress.Maui.it.resx` will be applied to your application when device language is set to **Italian**.
1. Add the newly created resource to your application.
1. Make certain that the `.UseDevExpress` method parameter is set to `true`. Refer to the [Localization help topic](https://docs.devexpress.devx/MAUI/404120/localization?v=22.2) to learn more on the localization process.
1. **Optional**. If you want to share your translation with the community, fork this repository, add your resource file with the translated localization strings, and create a pull request for this repository.

## Documentation

[Localization](https://docs.devexpress.devx/MAUI/404120/localization?v=22.2)

## More Examples

[Localize Controls](https://github.com/DevExpress-Examples/maui-localization)
