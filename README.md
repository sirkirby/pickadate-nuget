# pickadate.js #

pickadate js nuget package. For more info on the project, visit the main site http://amsul.ca/pickadate.js/

## Build ##

![](http://build.ryantechframework.com/app/rest/builds/buildType:%28id:NugetPackages_PickADateNuget%29/statusIcon)

Install the grunt cli tools

`npm install -g grunt-cli`

Install the required modules

`npm install`

build the package to the `dist` folder

`grunt`

## Installing ##
From within the Visual Studio nuget package manager powershell console. https://www.nuget.org/packages/pickadate

`PM> install-package pickadate`


## ASP.Net Bundling & Minification ##
Scripts for date picker, time picker, or both

    bundles.Add(new ScriptBundle("~/bundles/pickadate/date").Include("~/Scripts/pickadate/picker.js", "~/Scripts/pickadate/picker.date.js"));

    bundles.Add(new ScriptBundle("~/bundles/pickadate/time").Include("~/Scripts/pickadate/picker.js", "~/Scripts/pickadate/picker.time.js"));

    bundles.Add(new ScriptBundle("~/bundles/pickadate/all").Include("~/Scripts/pickadate/picker.js", "~/Scripts/pickadate/picker.date.js", "~/Scripts/pickadate/picker.time.js"));

Styles for default and classic themes

    bundles.Add(new StyleBundle("~/Content/pickadate/themes/default").Include("~/Scripts/pickadate/themes/default.css", "~/Scripts/pickadate/themes/default.date.css", "~/Scripts/pickadate/themes/default.time.css"));

    bundles.Add(new StyleBundle("~/Content/pickadate/themes/classic").Include("~/Scripts/pickadate/themes/classic.css", "~/Scripts/pickadate/themes/classic.date.css", "~/Scripts/pickadate/themes/classic.time.css"));

# [License](LICENSE.txt) #