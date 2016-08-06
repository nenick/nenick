# My User GitHub Page

Based on [Bootstrap freelancer] project and ported to be build with Jekyll.

## Project Structure

### Root

| File        | Content |
|-------------|---------|
| _config.yml | basic configuration for Jekyll, don't place page specific content here |
| *.html      | pages definitions for this site and his textual contents |

### Sub Folders

| Folder    | Content |
|-----------|---------|
| _data     | global accessible textual contents |
| _includes | blocks of widgets used in page layouts |
| _layouts  | layouts definition for pages |
| _posts    | collection of blog articles |
| assets    | whiles which are not simple text or images (pdf, ...) |
| css       | style settings for this site |
| img       | collection of site images |
| js        | Java scripts for dynamic site effects |
| mail      | script to send  mails |
| vagrant   | development environment to build Jekyll pages, [how to use](vagrant/README.md) |
| vender    | third party libraries |


[Bootstrap freelancer]: https://github.com/BlackrockDigital/startbootstrap-freelancer

## Create CV

Import Xing profile at Lebenslauf.com and modify ...

* Remove "Anschrift" which should not be public
* Translate "gebohren am" -> Date of birth
* Translate "Berufliche Laufbahn" -> Work Experience
* Translate x "Juli" -> July
* Translate "Akademische Laufbahn" -> Education
* Translate x "Abschluss" -> degree
* Translate x "Abschluss" -> degree
* Download as PDF and put into assets folder
