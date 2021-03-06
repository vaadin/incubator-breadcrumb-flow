# Deprecated 
This repository has been deprecated. Please find the latest code here: 
https://github.com/vaadin-component-factory/breadcrumb

# Incubator Breadcrumb for Flow

Incubator Breadcrumbs for Flow is server-side component of [incubator-breadcrumbs](https://github.com/vaadin/incubator-breadcrumb) web component for Vaadin 10. 
It is a Web Component providing an easy way to display breadcrumb on web pages.

[<img src="https://raw.githubusercontent.com/vaadin/incubator-breadcrumb/master/screenshot.png" width="200" alt="Screenshot of incubator-breadcrumbs">](https://vaadin.com/directory/components/vaadinincubator-breadcrumbs)
## Usage

Create instance of `Breadcrumbs` and instances of `Breadcrumb`. You can set breadcrumb text and href. 
Also you can set property shift, which will indicate whether breadcrumb should be hidden for 
mobile view(when viewport is smaller then 420px).
```
Breadcrumbs breadcrumbs = new Breadcrumbs();
breadcrumbs.add(
    new Breadcrumb("Home","breadcrumbs/#", true),
    new Breadcrumb("Components", "breadcrumbs/#", true),
    new Breadcrumb("Incubator Components", "breadcrumbs/#"),
    new Breadcrumb("Breadcrumbs"));
```
Breadcrumbs "Home" and "Components" will be hidden when viewport is less then 420px  

## Demo
To run demo go to `incubator-breadcrumbs-flow-vaadincom-demo/` subfolder and run `mbn jetty:run`.
After server startup, you'll be able find demo at [http://localhost:8080/breadcrumbs](http://localhost:8080/breadcrumbs)

## Setting up for development:

Clone the project in GitHub (or fork it if you plan on contributing)

```
https://github.com/vaadin/incubator-breadcrumb-flow
```

To build and install the project into the local repository run 

```mvn install ```

## License & Author

This Add-on is distributed under [Commercial Vaadin Add-on License version 3](http://vaadin.com/license/cval-3) (CVALv3). For license terms, see LICENSE.txt.

Incubator Breadcrumb is written by Vaadin Ltd.

