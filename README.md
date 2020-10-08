# AngularChart
![Screenshot (4)](https://user-images.githubusercontent.com/60258353/95459792-f8a77d00-0928-11eb-8113-6641c871040f.png)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.2.
step-1 install angular 2QR code module(npm install angular2-qrcode)
step-2 import QRModule in app module
step-3 implement QRCode generator (<qr-code [value]="'www.positronx.io'"></qr-code>)


## QR Properties 
1. value = Takes a String value and convert String to QR Code,
2.size = sets up the height and width of the QR code(default is 100)
3. level = (‘L’, ‘M’, ‘Q’, ‘H’).
4.bacground = The default value is white.
5. backgroundAlpha =Sets up the opacity of the foreground
6.mime = used for setting up the mime type for the output image.
7.padding=  sets up the padding in QR Code,
8. canvas =The value type is boolean and used for outputting a canvas element if sets to true. However, the default value is set to false.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
