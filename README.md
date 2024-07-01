# Red Book for Free Imagery <a href='https://yercizenler.org'><img src='https://yercizenler.org/wp-content/uploads/2018/09/yer-cizenlerlogo.png' align="right" height="139" /></a>

Very high-resolution (<0.5m) aerial and satellite imagery is crucial in pre- and post-disaster scenarios. However, the licenses associated with these images often restrict their use, making them legally inaccessible for most purposes. This document aims to provide you, the GIS professionals, disaster response organizations, and individuals seeking access to high-resolution aerial imagery with a guide to imagery sources that offer licenses, allowing for a wide range of use cases, especially during a crisis. We focus on very high-resolution imagery since they are usually required to digitize physical features for maps like OpenStreetMap.

> [!CAUTION]
> Disclaimer: Each use is a different intellectual, geopolitical, and economic case. There is no guarantee that the guidance is valid for your case. And yes, surprise, it's not a legal advice.

> [!NOTE]
> Feel free to add your experience and tips for countries and use cases in the details section.

#### Table of Contents
- [Where is Imagery?](#where-is-imagery)
- [Data Licensing](#data-licensing)
- [Where is Free Imagery?](#where-is-free-imagery)
- [Details](#details)
  - [Use-case specific](#use-case-specific-details)
  - [Country specific](#country-specific-details)

## Where is Imagery?
Currently, there are many providers for very high-resolution imagery (via satellites, aerial vehicles, drones, etc). Governments or private companies (in tight relations with governments) such as Airbus, Maxar, Planet, and many others have their operations in space or air. Both governments and private companies usually distribute data with 3rd-party companies or institutions. It's not easy to access them without the distributors. There are also community-driven initiatives such as [OpenAerialMap](https://openaerialmap.org), where people publish their proprietary imagery with free licenses or already free licensed data.

During disasters, many satellite providers contact [International Disaster Charter](https://disasterscharter.org/web/guest/about-the-charter) to align on imagery acquisitions. Although you can see the images acquired on the activations, the charter does share data with you if you meet the criteria mentioned [here](https://disasterscharter.org/web/guest/how-to-register-as-a-user). Governments, local initiatives, and international NGOs also operate imaging with aerial vehicles and drones. Most of the images have proprietary rights, avoiding many of the use cases for public initiatives.

## Data Licensing
Depending on your use case, in which part of the Earth you are, your budget, and many other entangled legal and bureaucratic systems, you are not free to use the imagery you see on your screen. For our scope, [this guidance](https://gkhub.earthobservations.org/packages/p0zg8-02b56) and [this article](https://joemorrison.medium.com/the-commercial-satellite-imagery-business-model-is-broken-6f0e437ec29d) are a nice summary of the issues related to legal and economic boundaries. If you use imagery without proper rights, it's up to the providers to claim copyright infringement.

Usually, [Creative Commons licenses](https://creativecommons.org/share-your-work/cclicenses/) enable people to create derivative work on the imagery and publish it to the public. Recommended types are listed by [GEO Data and Knowledge Working Group](https://earthobservations.org/organization/working-groups/geo-data-working-group) in [this guide](https://gkhub.earthobservations.org/packages/p0zg8-02b56) Imagery providers are encouraged to publish their data with such licenses so that the people can take action with minimal legal concerns. If the imagery does not have such a license, it's best to specify your use case in the permit.

## Where is Free Imagery?
Only in some places. The sources below are usually the only ones if your government does not share imagery with the public.

#### Sources
- [OpenAerialMap](#OpenAerialMap)
- [Maxar Open Data Program](#Maxar-Open-Data-Program)
- [Planet](#Planet)
- [Esri World Imagery](#Esri-World-Imagery)
- [Microsoft Bing](#Microsoft-Bing)
- [Others](#Others)

### OpenAerialMap
<a href='https://openaerialmap.org'><img src='https://openaerialmap.org/assets/graphics/meta/oam-logo-h-pos.svg' align="right" height="100" width="200" /></a>
[OpenAerialMap](https://openaerialmap.org) is a great platform initiated by [Humanitarian OpenStreetMap Team](https://www.hotosm.org/) and maintained by [Kontur](https://www.kontur.io/) to distribute free licensed data during disasters. The platform clarifies license issues and distributes data in a very efficent way so that you think less about technical details. There are volunteers like us to monitor the events and upload data to OAM.

During disasters, usually, HOT representatives use OAM base map to edit OpenStreetMap Point of Interests (POI) collaboratively thanks to [the mosaic layer](https://www.kontur.io/solutions/global-orthomosaic-layer/) provided by Kontur.

### Maxar Open Data Program
<a href='https://www.maxar.com/open-data'><img src='https://www.maxar.com/assets/navbar/maxar-logo-navbar-b16b65d2d6b07ad4cd5fb17b016835a20a6a359158d832293402e231fca26e13.svg' align="right" height="100" width="200" /></a>
[Maxar Open Data Program](https://www.maxar.com/open-data) is by far the most helpful program offering satellite imagery with a [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license, which enables crucial use cases such as digitizing features to upload to OpenStreetMap. Thanks to volunteers uploading, you can usually access their imagery through OpenAerialMap.

### Planet
<a href='https://www.planet.com/disasterdata/'><img src='https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Planet_Labs_logo.svg/480px-Planet_Labs_logo.svg.png' align="right" height="100" width="200" /></a>
Planet does not share data as openly as Maxar, but they are quite active and responsive during disasters and likely to share data with you if you are after using data for public benefit. You should contact them through their [disaster data page](https://www.planet.com/disasterdata/).

### Esri World Imagery
<a href='https://www.arcgis.com/home/item.html?id=10df2279f9684e4a9f6a7f08febac2a9'><img src='https://upload.wikimedia.org/wikipedia/de/thumb/4/46/ESRI_Logo.svg/1416px-ESRI_Logo.svg.png?20111006175738' align="right" height="40" width="200" /></a>
Esri enables users on OpenStreetMap to use their base map to edit POIs, as mentioned [here](https://wiki.openstreetmap.org/wiki/Esri). You can and should facilitate OpenStreetMap for many use cases.

### Microsoft Bing
<a href='https://www.bing.com/maps/'><img src='https://upload.wikimedia.org/wikipedia/commons/e/e8/Microsoft_Bing_logo.svg' align="right" height="40" width="200" /></a>
Esri enables users on OpenStreetMap to use their base map to edit POIs as mentioned [here](https://wiki.openstreetmap.org/wiki/Bing_Maps). You can and should facilitate OpenStreetMap for many use cases.

### Others
Some governments already provide imagery to OpenStreetMap editors or have open data programs. If you don't have an open data program, you probably need to handle complex communication steps to get access. It's worth mentioning new providers such as [Umbra](https://umbra.space/), which is now manipulating the industry with courageous [licensing offerings](https://joemorrison.substack.com/p/how-to-change-an-industry).

## Details

### Use-case Specific Details

#### Cases
- [Using data to edit POIs in OpenStreetMap](#Using-data-to-edit-POIs-in-OpenStreetMap)

#### Using data to edit POIs in OpenStreetMap
During disasters, it's best to sync with Humanitarian OpenStreetMap Team representatives to determine which license is required for imagery to edit POIs and upload to OpenStreetMap. For other use cases, you can find further details in [wiki](https://wiki.openstreetmap.org/) for resources.


### Country Specific Details

#### Countries
- [:tr: Turkey](#Turkey)

### Turkey
The Turkish government doesn't have an open imagery program, and it's also not very easy to access data. Feel free to contact the members of Yercizenler for further guidance.
