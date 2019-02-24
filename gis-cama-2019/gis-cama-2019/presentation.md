<!-- .slide: class="title" -->

## Extending the Capabilities and Offerings of your GIS: A guided tour of Esri’s Developer Resources
Mara Stoica, Justin Colville & Matt Bryant
<br><br><br>

Follow along at [http://esriurl.com/giscama2019](http://esriurl.com/giscama2019)

---

<!-- .slide: class="agenda" -->

## Agenda

- Introduction
- Configure
- Customize
- Break
- Develop
- Wrap-up
- Questions

---

<!-- .slide: class="section" -->

# Introduction

---

<!-- .slide: class="bg-7" -->

<div class="container">
    <div class="col" style="text-align:left">
        ![Esri](images/small-logo.png)<br>
        Mara Stoica<br>
        .NET Software Engineer<br>
        Esri<br>
        [mstoica@esri.com](mailto:mstoica@esri.com)
    </div>
    <div class="col" style="text-align:left">
        ![Esri](images/small-logo.png)<br>
        Justin Colville<br>
        Product Engineer<br>
        Esri<br>
        [jcolville@esri.com](mailto:jcolville@esri.com)
    </div>
    <div class="col" style="text-align:left">
        ![DEVNET](images/devnet-d-icon.png)<br>
        Matt Bryant<br>
        Chief Technology Officer<br>
        DEVNET<br>
        [bryant@devnetinc.com](mailto:bryant@devnetinc.com)
    </div>
</div>

---

<!-- .slide: class="bg-5" -->

## Apps and Builders and APIs, oh my?

There are a lot of options for extending the ArcGIS platform.<br>
Consider your users and team needs.<br>
Choose the right tools for the solution.

---

<!-- .slide: class="bg-5" -->

<div class="container">
    <div class="col" style="text-align:left">
        <h3>Configuration</h3>
        The process of setting up options using the administrative tools supplied within the application.
    </div>
    <div class="col" style="text-align:left">
        <h3>Customization</h3>
        Modification of the base product itself though code.
    </div>
    <div class="col" style="text-align:left">
        <h3>Development</h3>
        Creation of custom solutions that run independently of other systems.
    </div>
</div>

---

<!-- .slide: class="bg-5" -->

## Resources

[doc.arcgis.com](https://doc.arcgis.com/)<br>
[solutions.arcgis.com](https://solutions.arcgis.com/)<br>
[developers.arcgis.com](https://developers.arcgis.com/)

---

<!-- .slide: class="section" -->

# Configure

---

<!-- .slide: class="background" -->

## Field Operations

 - Suite of purpose-built apps working together<br>
  - [Collector](https://www.esri.com/en-us/arcgis/products/collector-for-arcgis/resources)
  - Explorer
  - Workforce
  - Navigator
  - Tracker
  - [Survey123](https://www.esri.com/en-us/arcgis/products/survey123/resources)

---

<!-- .slide: class="bg-5" -->

## Data Collection

 - Collector
  - Map centric
 - Survey123 - Form based
 - Partner integration
  - Eos Positioning + LTI
  - Trimble - R1/R2/R102 integration

---

<!-- .slide: class="bg-5" -->

## Tracking and Viewing

 - Tracker
 - Explorer

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer | ✔️ | ❌ | ❌ |
| Survey123 | ✔️ | ❌ | ❌ |

---

<!-- .slide: class="background" -->

## Arcade

---

<!-- .slide: class="bg-5" -->

## Arcade

Simple and portable expressions language<br>
[developers.arcgis.com/arcade](https://developers.arcgis.com/arcade/)<br>
[Toronto Neighborhoods Urban Trees](http://jsapi.maps.arcgis.com/home/item.html?id=2b998111603f4cd4bf135647b24b21b6)<br>
[What’s new with Arcade: Taking a stroll through FeatureSets](https://www.esri.com/arcgis-blog/products/mapping/mapping/whats-new-with-arcade-taking-a-stroll-through-featuresets-part-2/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |

---

<!-- .slide: class="background" -->

## Operations Dashboard

[Dashboard](https://doc.arcgis.com/en/operations-dashboard/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |

---

<!-- .slide: class="background" -->

## Web AppBuilder<br><br>

Configurable web mapping application<br>
Choose from several pre-made themes<br>
Add functionality with pre-built widgets<br>
[https://doc.arcgis.com/en/web-appbuilder](https://doc.arcgis.com/en/web-appbuilder/)

---

<!-- .slide: class="background" -->

<div class="container">
    <div class="col">
        ![Floodplain Inquiry](http://solutions.arcgis.com/shared/img/FloodInquiryOverview.png)<br>
        [Floodplain Inquiry](https://www.arcgis.com/apps/webappviewer/index.html?id=c2b1439f82a14d2390a9197da6758d83)
    </div>
    <div class="col">
         ![Residential Comp Finder](http://solutions.arcgis.com/local-government/help/residential-comp-finders/img/overview.png)<br>
         [Residential Comp Finder](http://statelocaltryit.maps.arcgis.com/apps/webappviewer/index.html?id=2e5abc40d59745f486eb41f05e46d38d)
    </div>
</div>

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ |   |  |

---

<!-- .slide: class="section" -->

# Customize

---

<!-- .slide: class="background" -->

## Web AppBuilder<br><br>

Create custom widgets<br>
Create custom themes<br>
[https://developers.arcgis.com/web-appbuilder/](https://developers.arcgis.com/web-appbuilder/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |

---

<!-- .slide: class="background" -->

## AppStudio

[AppStudio](https://appstudio.arcgis.com/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |

---

<!-- .slide: class="background" -->

## ArcGIS Pro DSK

Create Pro add-ins and solution configurations using C# or Visual Basic<br>
[ArcGIS Pro SDK](https://pro.arcgis.com/en/pro-app/sdk/)<br><br>

Create an add-in with a button<br>
[https://developers.arcgis.com/labs/pro/build-your-first-add-in/](https://developers.arcgis.com/labs/pro/build-your-first-add-in/)<br><br>

Create an add-in with an identify tool<br>
[https://developers.arcgis.com/labs/pro/build-a-map-identification-tool/](https://developers.arcgis.com/labs/pro/build-a-map-identification-tool/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |

---

<!-- .slide: class="background" -->

## Arcpy

Arcpy

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |

---

<!-- .slide: class="section" -->

# Develop

---

<!-- .slide: class="background" -->

## ArcGIS API for Python

[ArcGIS API for Python](https://developers.arcgis.com/python/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |
| ArcGIS API for Python |  ❌ | ❌ | ✔️ |

---

<!-- .slide: class="background" -->

## JavaScript API

Build custom web applications<br>
[https://developers.arcgis.com/javascript/](https://developers.arcgis.com/javascript/)<br><br>

Get started with tutorials<br>
[https://developers.arcgis.com/labs/](https://developers.arcgis.com/labs/)<br><br>

Create map app<br>
[https://developers.arcgis.com/labs/javascript/create-a-starter-app/](https://developers.arcgis.com/labs/javascript/create-a-starter-app/)<br><br>

Create webmap app<br>
[https://developers.arcgis.com/labs/javascript/display-a-web-map/](https://developers.arcgis.com/labs/javascript/display-a-web-map/)<br><br>

Add map coordinates widget<br>
[https://developers.arcgis.com/labs/javascript/get-map-coordinates/](https://developers.arcgis.com/labs/javascript/get-map-coordinates/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |
| ArcGIS API for Python |  ❌ | ❌ | ✔️ |
| Javascript API |  ❌ | ❌ | ✔️ |

---

<!-- .slide: class="background" -->

## Runtime APIs

Runtime APIs

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  | ✔️ |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |
| ArcGIS API for Python |  ❌ | ❌ | ✔️ |
| Javascript API |  ❌ | ❌ | ✔️ |
| Runtime APIs |  ❌ | ❌ | ✔️ |

---

<!-- .slide: class="questions" -->

## Questions

---

<!-- .slide: class="end" -->

![Esri](images/logo.png)
