# GURPS Character Sheet Library Data

GURPS Character Sheet (GCS) is a stand-alone, interactive, character sheet editor that allows you to
build characters for the [GURPS](http://www.sjgames.com/gurps) 4<sup>th</sup> Edition roleplaying
game system.

This repository holds the library data files for the [GCS project](https://github.com/richardwilkes/gcs).

Most of the data here has been entered in by users of GCS and contributed back to the project for
everyone to make use of. If you see mistakes or ommissions that you've fixed in your copy, or have
data files you'd like to contribute, please create a Pull Request to get them merged into the master
library. If that isn't something you know how to do, you can also create an Issue and attach the
file(s) containing your changes to it, along with an explanation of what it is you changed.

---

Some guidelines for creating Guns & Ammo recommended by one of GCS's users:
* Rifle Slings, and similar equipment, should be built as Containers, and, when specified by a
  reliable source or from authoritative experience, feature the Prerequisite “Maximum Contained
  Weight”.
* Stripper Clips, Moon Clips, En-Bloc Clips, Disintegrating and Non-Disintegrating Belts, Magazines,
  and Speed-Loaders (hereafter referred to as “Cartridge Containers”, for convenience) should be
  built as Containers with a Prerequisite “Maximum Contained Quantity”, except where a reliable
  source or authoritative experience clearly indicates otherwise.
* Cartridge Containers should be Named according to their Manufacturer, Product Name, Model, Gun
  Compatibility, Cartridge Container Type, Caliber, and Number of Rounds, as available information
  allows (Example: “Stripper Clip, .30-06, 10 Rounds"; “Zillika SMG Magazine, 9x19mm, 30 Rounds").
* Cartridge Container Empty Weights should be reverse-engineered from the GURPS as-published “Loaded
  Weight” of the Cartridge Container, and the as-published Weight of the total contained Cartridges,
  as per HT175.
* Non-published TL5-TL8 Cartridge Containers should still use HT175 as a Reference, and should be
  constructed according to a reliable source or from authoritative experience, when possible.
* Multiple Rounds should be added to Cartridge Containers with Quantity, and not with Copying and
  multiple Pastes, or Duplication.
* Different Rounds loaded into the same Cartridge Container (such as Tracers shuffled in with other
  Rounds) should be in single groups of each type, with the Cartridge Container’s Notes explicitly
  declaring the exact ordering in firing order.
* Cartridge Containers should be Saved while left Open when they are loaded into a Gun, the first
  Empty Cartridge Container not loaded into a Gun, or the first Cartridge Container that is Full of
  a particular kind/arrangement of Rounds, and should be Saved while left Closed only when otherwise.
* Guns should be Named according to their Manufacturer, Product Name, Model, Type, and Caliber, as
  available information allows.
* Guns of various types should be built as Containers with an Empty Weight to be reverse-engineered
  from the GURPS as-published “Loaded Weight” of the Gun (when it isn’t explicitly indicated as
  “Empty Weight”, or some other Weight), the as-published “Loaded Weight” of External (i.e., not
  internal, such as “Internal Magazine”) Cartridge Containers, and the as-published Weight of the
  total contained Cartridges, as follows:
    * Improvisationally loaded Guns (muzzle-loaded weapons of varying kinds, or anything where the
      shot and powder are variable) should not have either a Prerequisite Maximum Contained Quantity
      or Maximum Contained Weight; if listed as “Loaded Weight”, and not “Empty Weight”, defer to a
      reliable source or authoritative experience to determine the Empty Weight.
    * Revolvers should have a Prerequisite Maximum Contained Weight, which, ideally, should
      accommodate the heaviest possible Rounds of appropriate Caliber at its maximum number of Shots,
      and, only for Revolvers compatible with Moon Clips, also accommodating the additional weight
      of Moon Clips; the Empty Weight should be assumed to be the Fully Loaded Weight without the
      total Weight of typical Cartridges, and not without the Weight of the Moon Clip.
    * Rifles that take Paper or Full Cartridges should have a Prerequisite Maximum Contained Quantity
      of the maximum number of Shots; the Empty Weight of the Gun should be assumed to be the Fully
      Loaded Weight of the Gun without the total Weight of typical Cartridges.
    * Rifles that take En-Bloc Clips or Magazines should have a Prerequisite Maximum Contained
      Quantity of 1, for the Clip or Magazine; the Empty Weight of the Gun should be assumed to be
      the Fully Loaded Weight of the Gun without the Weight of the Fully Loaded En-Bloc Clip or Fully
      Loaded Magazine.
