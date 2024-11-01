=== Table Reservation ===

Contributors: vanadiuz
Author URI: https://true-emotions.studio
Plugin URL: https://github.com/vanadiuz/table-reservation
Donate link: https://www.paypal.me/trueemotions
Tags: table reservation, restaurant reservations, reservations, table bookings, bookings
Requires at least: 4.9
Tested up to: 5.0.3
Stable tag: 5.0.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Selectable tables! No collisions between reservations. Rich settings 🔧 and Mobile UX.

== Description  ==

This plugin allows users quickly book a table in your cafe or make a restaurant reservation. Also it can be used for coworking, internet cafe (cybercafe) and nightclub.

* [**Demo**](https://true-emotions.studio/sample-page/) 👀
* **Contribute on** [**GitHub**](https://github.com/vanadiuz/table-reservation) 🔨

**Features 👓**

*Essential* 👊:

* Rich schedule settings: *opening hours, week days, holidays, siesta...* 
* Custom email notifications for admin and guests
* Selectable tables for reservations *(one table can't be reserved by different people simultaneously, e.g. no collisions)*
* Add and edit bookings from the admin panel
* Check correctness of user-input data *(date, party, time, name, email, phone, message)*
* GDPR compliant

*Appearance* 👠:

* Mobile UX
* Customisable colors, date/time format, titles etc.
* Visual Composer compatible

[*Pro Version*](https://true-emotions.studio/products/plugins/table-reservation-pro/ "Pro Version!!!") 🔥:

* Unlimited venues: *restaurants, cafes, clubs etc.*
* Advanced reservations manage system: *create/delete reservations*
* Each venue has its own page and booking form
* Selectable duration of visit
* Quick support (<12 h.)

== Frequently Asked Questions ==

= How to start =

You will find "Cafe" and "Reservations" menu in your WordPress admin panel.

 1) Create scheme (Cafe -> Add new -> set featured image, select name of your cafe, draw tables markup)
 2) Add shortcode to page 
 3) Setup schedule (Cafe -> Settings)	

[Slightly outdated video](https://data.true-emotions.studio/plugins/trem-table-reservation/table-reservation.mp4)

= Shortcode? =

[table-reservation]. 

= How to customize appearance of this plugin? =

1) There is possibility to change colors in Cafe-> Settings.
2) Also you can override styles in assets->css->tremtr-client.css, but you can't change HTML markup, because it very hard.

= How to create beautiful email template? 🌻 =

[Here!](http://telegra.ph/How-create-beautiful-email-template-01-26 "And write code!")

= Can I change the date/time format? =

Yes, set the format for front-end the datepicker in Cafe > Settings. 

= How to translate the plugin? =

Everything in this plugin can be translated using the standard translation process and software like PoEdit. 
🔸 The language of the calendar is selected separately in the settings of the cafe (default English, uk = Ukrainian). 
🔸 Files with translation (for example "tremtr-ru_RU") must be placed in the …\wp-content\languages\plugins\. 

It could be wonderful if you share your translation with other users.🤙 You can upload somewhere an archive with .mo and .po files and drop the link on the support forum, or make a pull request on the GitHub.

= Can I set up many venues/cafes/locations? =

In [Pro-Version]( https://true-emotions.studio/products/plugins/table-reservation-pro/ )!


= GDRP? =

All user data is automatically deleted in 24 hours after the reservation time. In other words, the plugin doesn't store information about users after the moment when the reservation is not relevant. Data is collected solely for table reservation purposes. No additional processing of information and compilation of statistics is carried out.


= Plugin does not work!😭 =

* Select "Post name" in Settings->Permalinks!!!
* If you use W3 Total Cache(or another cache), you should turn off js minification to make everything work.
* Please note that up to TWO time intervals for one day can be specified in the schedule!
* The PHP version should be as fresh as possible (7 and above).

## Changelog
#### 3.3.3/4 (2018-09-01)
* Added PT_BR Translation ©mtoledo62

#### 3.3.3/4 (2018-12-31)
* Modified table-reservation.php (site_url -> home_url), micro update.

#### 3.3.3 (2018-06-12)
* Added German translation (Thanks to Faruk Catal <faruk@3moon.de>)

#### 3.3.2 (2018-05-31)
* Privacy notice (GDRP)

#### 3.2.10 (2018-05-22)
* Siesta in the schedule
* Improved Russian translation

#### 3.2.8 (2018-04-05)
* Added Russian translation

#### 3.2.7 (2018-03-31)
* Added spinner for beauty
* Fixed bug with times for today
* Fixed bug free tables
* Added Italian translation (thanks to Enrico Strozzi)

#### 3.2.6 (2018-03-30)
* Added italian translation to calendar
* Fixed bug with AM/PM time formats

#### 3.2.5 (2018-03-23)
* Several appearance improvements (remove crazy sliding)
* Fixed small bug with reservations
* Fixed bug with WPBakery
* Remove emails reject form


#### 3.2.4 (2018-03-18)
* Added more time intervals between each available time

#### 3.2.3 (2018-03-15)
* Fixed bug reservations at night
* Fixed bug with shedule without exceptions
* Exceptions for "all day" become unselectable in calendar
* Fixed bug with very narrow cafes schemes
* Fixed bug with disabled, but not reserved tables
* Fixed bug with localization calendar date (for non-english cases)
* Cafes name now is a name of the post where cafes scheme created
* Added transition effect to time carousel


#### 3.2.1 (2018-03-14)
* Fixed bug related with date

#### 3.2.0 (2018-03-14)
* Working after midnight! 🌘

#### 3.1.2 (2018-03-12)
* Update .pot

#### 3.1.1 (2018-03-11)
* Add Trem Logo

#### 3.1 (2018-03-11)
* Essential improved mobile UX

#### 3.0 (2018-03-08)
* New way for time selection
* Add Reservation Duration setting
* Fixed bug with time exceptions
* Minor improvements

#### 2.1 (2018-02-23)
* Fixed critical bug with reservations
* Improved table creating process
* And other minor improvements

#### 1.0 (2017-11-29)
* Email Templates for Restaurant Reservations
* Restaurant reservation module
* Reservation notifications
* Schedule reservations