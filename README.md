# ODSPilotLog
Recording of pilot flight time facilitating aircrafts and aerodromes lookups.

Pilot log documents created from this template are useful to perform flight log calculations, as backup, and to verify consistency of the paper flight logs mandated by law.

## Disclaimer

Pilot log documents created from this template on their own do not meet the legal requirements for flight crew recording of flight time, due to the lack of auditability and the lack of support for signing records and endorsements.

## Before First Use

After creation of your pilot log spreadsheet from this template

 - populate the 'Aircrafts' table with the aircrafts you operate. Be careful to remove the "nonsense" placeholder example.
 - Extend the 'Aerodromes' table by the aerodromes you use.

The template  'Aerodromes' table is pre-filled with the set of aerodromes the author had the pleasure to visit as of now. It doesn't hurt to retain these, but feel free to adapt the table as needed.

You may fill in your pilot personal data in 'Custom Properties': name, address, date and place of birth.

## Maintainig Aircrafts and Aerodromes Tables

Each time you use a new aircraft or new aerodrome you need to extend these tables, before being able to use the new values in flight log entries. Remember to sort 'Aircrafts' and 'Aerodromes' tables by their first columns -- excluding title rows -- after adding new records. Otherwise, lookups from the flight log will fail.

## Flight Log Columns auto-filled by Formulas

All ten columns completed by table lookups or formulas are shaded grey. You shouldn't need any manual intervention to fill these, unless you need to record a flight of 24 h or longer, or an airfield without ICAO location indicator.

This template initially provides 500 empty flight log records to be filled. When used up, extend the grey formula group colums as needed.

## Logging Flights of  24 Hours or Longer

Whenever the recorded arrival time is before departure time, flight time computation assumes that the flight spanned across midnight, but for at most 23:59 h. In case the flight actually lasted longer, you can substitute the formula _in that particular cell_ by the correct duration, which will then also be used in accumlated time calculations. Be careful _not_ to substitute values in other cells, in particular _not_ to accidentally pull a substitute value downwards to extend the 'Flight Time' column.

## Logging Aerodromes Without an ICAO Location Indicator.

Enter 'ZZZZ' in the 'From' or 'To' column 'ICAO'. The corresping 'Name' field will then display 'Insert name'. Replace the lookup expression _in that particular cell_ by the actual aerodrome name. Be careful _not_ to substitute values in other cells, in particular _not_ to accidentally pull a substitute value downwards to extend the aerodrome 'Name' column.

## Accumulated Flight Times and Numbers of Landings

The five rightmost colums of the 'Flight Log' sheet are computing accumulated flight times and numbers of landings, including the current row, and _limited to filtered rows_. To determine accumulated values for a specific subset, e.g. a set of aircraft types or flights logged as PIC, use the title row filters to restrict the display as needed.

## Copying

Copyright (c) 2022 Dr. Michael Steffens

This OTS template is provided under the terms of GNU General Public License v3.0. The author does neither claim any rights, nor accept liabilities, with respect to pilot log documents created from this template.

	SPDX-License-Identifier:	GPL-3.0
