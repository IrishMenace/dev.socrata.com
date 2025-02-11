---
layout: with-sidebar
sidebar: documentation
title: Data Transform Listing
---

These are the transformation functions available in the [Dataset Management API](/publishers/dsmapi.html).
These functions can be used to transform and validate your data before you publish
your dataset for consumption.

These functions can be used in the "Data Transforms" editor of the the [Dataset Management Experience](https://support.socrata.com/hc/en-us/articles/115016067067-Using-the-Socrata-Data-Management-Experience) interface. Check out some of the examples on our Support Portal [here](https://support.socrata.com/hc/en-us/articles/360034530954-Data-Transformation-Examples)!

See the [Dataset Management API docs](https://socratapublishing.docs.apiary.io/) for more info on how to use the transform functions as an API user.



| Function Name | Description |
| ---- | ---- |
| [`+`](/docs/transforms/add.html) |   Keep a number's sign |
| [`and`](/docs/transforms/and.html) |   Logical and of two boolean values |
| [`||`](/docs/transforms/concatenate.html) |   concatenate two strings |
| [`/`](/docs/transforms/divide.html) |   Divide a number by another |
| [`=`](/docs/transforms/equal.html) |   Return true if the left side equals the right |
| [`==`](/docs/transforms/equal.html) |   Return true if the left side equals the right |
| [`^`](/docs/transforms/exponent.html) | No documentation is available. |
| [`>`](/docs/transforms/greater_than.html) |   Return true if the value on the left is greater than the value on the right |
| [`>=`](/docs/transforms/greater_than_equal.html) |   Return true if the value on the left is greater than or equal to the value on the right |
| [`<`](/docs/transforms/less_than.html) |   Return true if the value on the left is less than the value on the right |
| [`<=`](/docs/transforms/less_than_equal.html) |   Return true if the value on the left is less than or equal to the value on the right |
| [`%`](/docs/transforms/modulo.html) |   Find the remainder(modulus) of one number divided by another |
| [`*`](/docs/transforms/multiply.html) |   Multiply two numbers together |
| [`not`](/docs/transforms/not.html) |   Invert a boolean |
| [`<>`](/docs/transforms/not_equal.html) |   Return true if the left side does not equal the right |
| [`!=`](/docs/transforms/not_equal.html) |   Return true if the left side does not equal the right |
| [`or`](/docs/transforms/or.html) |   Logical or of two boolean values |
| [`-`](/docs/transforms/subtract.html) |   Subtract a number from another |
| [`abs`](/docs/transforms/abs.html) |   Produce the absolute value of a number |
| [`between`](/docs/transforms/between.html) |   Return true if the left is within the range of the right values |
| [`case`](/docs/transforms/case.html) |   Evaluate a series of true/false expressions (predicates) and return the next consequent. |
| [`centroid`](/docs/transforms/centroid.html) |   returns the geometric centroid of a polygon or multipolygon. Please refer to |
| [`coalesce`](/docs/transforms/coalesce.html) |   Take the leftmost non-null value. |
| [`contains`](/docs/transforms/contains.html) |   tell whether or not a string contains another string |
| [`county_boundary`](/docs/transforms/county_boundary.html) |   Returns the boundary of the US county as a multipolygon. The state name is not case sensitive. |
| [`date_extract_d`](/docs/transforms/date_extract_d.html) |   Extract the day from the date as an integer |
| [`date_extract_dow`](/docs/transforms/date_extract_dow.html) |   Extracts the day of the week as an integer between 0 and 6 where |
| [`date_extract_hh`](/docs/transforms/date_extract_hh.html) |   Extract the hour the date as an integer |
| [`date_extract_m`](/docs/transforms/date_extract_m.html) |   Extract the month as an integer |
| [`date_extract_mm`](/docs/transforms/date_extract_mm.html) |   Extract the minute from the date as an integer |
| [`date_extract_ss`](/docs/transforms/date_extract_ss.html) |   Extract the second from the date as an integer |
| [`date_extract_woy`](/docs/transforms/date_extract_woy.html) |   Extracts the week of the year as an integer between 0 and 51 |
| [`date_extract_y`](/docs/transforms/date_extract_y.html) |   Extract the year as an integer |
| [`date_trunc_y`](/docs/transforms/date_trunc_y.html) |   Truncates a calendar date at the year threshold |
| [`date_trunc_ym`](/docs/transforms/date_trunc_ym.html) |   Truncates a calendar date at the year/month threshold |
| [`date_trunc_ymd`](/docs/transforms/date_trunc_ymd.html) |   Truncates a calendar date at the year/month/day threshold |
| [`datetime_add_d`](/docs/transforms/datetime_add_d.html) | Adds or subtracts the specified number of days to the timestamp |
| [`datetime_add_hh`](/docs/transforms/datetime_add_hh.html) | Adds or subtracts the specified number of hours to the timestamp |
| [`datetime_add_mm`](/docs/transforms/datetime_add_mm.html) | Adds or subtracts the specified number of minutes to the timestamp |
| [`datetime_add_ss`](/docs/transforms/datetime_add_ss.html) |   Adds or subtracts the specified number of seconds to the timestamp |
| [`datetime_diff`](/docs/transforms/datetime_diff.html) |   Calculates the difference between two dates in seconds, minutes, hours, days, business days, weeks, calendar weeks, months, or years. |
| [`domain_categories`](/docs/transforms/domain_categories.html) | Returns the categories currently configured on the domain. Useful primarily |
| [`domain_licenses`](/docs/transforms/domain_licenses.html) | Returns the licenses currently configured on the domain. Useful primarily |
| [`email_parse`](/docs/transforms/email_parse.html) |   Parse an email. This is best effort as most things are actually |
| [`ensure_within`](/docs/transforms/ensure_within.html) |   ensure_within is a function which takes a point and a multipolygon |
| [`error`](/docs/transforms/error.html) |   Make an error. This is useful in conjunction with a case function, |
| [`floating_timestamp_day`](/docs/transforms/floating_timestamp_day.html) |   Extract the day from a calendar date |
| [`floating_timestamp_day_of_week`](/docs/transforms/floating_timestamp_day_of_week.html) |   Extract the day of the week as an integer between 0 and 6 where Sunday is 0. |
| [`floating_timestamp_hour`](/docs/transforms/floating_timestamp_hour.html) |   Extract the hour from a calendar date |
| [`floating_timestamp_minute`](/docs/transforms/floating_timestamp_minute.html) |   Extract the minute from a calendar date |
| [`floating_timestamp_month`](/docs/transforms/floating_timestamp_month.html) |   Extract the month from a calendar date |
| [`floating_timestamp_second`](/docs/transforms/floating_timestamp_second.html) |   Extract the second from a calendar date |
| [`floating_timestamp_week_of_year`](/docs/transforms/floating_timestamp_week_of_year.html) |   Extract the week from a calendar date as an integer between 0 and 51. |
| [`floating_timestamp_year`](/docs/transforms/floating_timestamp_year.html) |   Extract the year from a calendar date |
| [`forgive`](/docs/transforms/forgive.html) |   forgive can take an optional default argument |
| [`from_polyline`](/docs/transforms/from_polyline.html) |   convert a linestring encode in Google's polyline format with the given precision to a Line |
| [`geocode`](/docs/transforms/geocode.html) |   geocode is a function which takes human readable addresses |
| [`geocode_esri`](/docs/transforms/geocode_esri.html) |   geocode_esri is a function which takes human readable addresses |
| [`grapheme_length`](/docs/transforms/grapheme_length.html) |   the length of a piece of text in unicode grapheme clusters. |
| [`greatest`](/docs/transforms/greatest.html) |   return the largest value among its arguments (ignoring null) |
| [`hash`](/docs/transforms/hash.html) |   Construct a hash value from a string value using either the md5 or sha256 algorithm. |
| [`haversine_distance`](/docs/transforms/haversine_distance.html) |   Return the distance of the line using haversine formula |
| [`http_get`](/docs/transforms/http_get.html) |   Make an HTTP Get request to a URL. The response is returned. If the server |
| [`in`](/docs/transforms/in.html) |   Whether or not a value is in a set of other values |
| [`is_empty`](/docs/transforms/is_empty.html) |   Returns whether or not the input is empty. Empty means null values, |
| [`is_not_null`](/docs/transforms/is_not_null.html) |   Whether or not a value is not null |
| [`is_null`](/docs/transforms/is_null.html) |   Whether or not a value is null |
| [`is_within`](/docs/transforms/is_within.html) |   is_within is a function which takes a point and a multipolygon |
| [`json_array_contains`](/docs/transforms/json_array_contains.html) |   Test if a json array contains an item. If the JSON passed to this function is not an array, |
| [`json_pluck`](/docs/transforms/json_pluck.html) |   Pluck a value out of a JSON string. The returned value will be a SoQL Json value. |
| [`json_pluck_boolean`](/docs/transforms/json_pluck_boolean.html) |   Pluck a boolean value out of a JSON string. The returned value must be a boolean, otherwise |
| [`json_pluck_number`](/docs/transforms/json_pluck_number.html) |   Pluck a number value out of a JSON string. The returned value must be a number, otherwise |
| [`json_pluck_text`](/docs/transforms/json_pluck_text.html) |   Pluck a text value out of a JSON string. The returned value may be a primitive like a |
| [`least`](/docs/transforms/least.html) |   return the smallest value among its arguments (ignoring null) |
| [`left_pad`](/docs/transforms/left_pad.html) |   Pad `text` with the minimum number of copies of `pad` to reach `desired_length`. |
| [`length`](/docs/transforms/length.html) |   the length of a piece of text in unicode code points.  This is usually, but not |
| [`like`](/docs/transforms/like.html) |   If a string is like another string. |
| [`location_address`](/docs/transforms/location_address.html) |   Extract the address from a location |
| [`location_city`](/docs/transforms/location_city.html) |   Extract the city from a location |
| [`location_point`](/docs/transforms/location_point.html) |   Extract the point from a location |
| [`location_state`](/docs/transforms/location_state.html) |   Extract the state from a location |
| [`location_to_point`](/docs/transforms/location_to_point.html) |   Turn a location value into a point |
| [`location_zip`](/docs/transforms/location_zip.html) |   Extract the zip from a location |
| [`lower`](/docs/transforms/lower.html) |   lowercase a string |
| [`make_location`](/docs/transforms/make_location.html) |   This function has been deprecated. Please use the make_point function instead. |
| [`make_point`](/docs/transforms/make_point.html) |   function to make a point out of a Y (latitude) and X (longitude) coordinate. |
| [`make_url`](/docs/transforms/make_url.html) | No documentation is available. |
| [`not_between`](/docs/transforms/not_between.html) |   Return true if the left is not within the range of the right values |
| [`not_in`](/docs/transforms/not_in.html) |   Whether or not a value is absent from a set of other values |
| [`not_like`](/docs/transforms/not_like.html) |   If a string is not like another string. |
| [`parse_address`](/docs/transforms/parse_address.html) |   Extract a street address from a full US address. |
| [`parse_city`](/docs/transforms/parse_city.html) |   Extract a city from a full US address. |
| [`parse_point`](/docs/transforms/parse_point.html) |   Extract the point from a full US address with point. |
| [`parse_state`](/docs/transforms/parse_state.html) |   Extract a state from a full US address. |
| [`parse_zip`](/docs/transforms/parse_zip.html) |   Extract a ZIP code from a full US address. |
| [`point_latitude`](/docs/transforms/point_latitude.html) |   Extract the latitude from a point |
| [`point_longitude`](/docs/transforms/point_longitude.html) |   Extract the longitude from a point |
| [`polylabel`](/docs/transforms/polylabel.html) |   Returns a point that must exist within the polygon borders. It uses the recursive grid-based algorithm described here: https://github.com/mapbox/polylabel#how-the-algorithm-works.  When given a multipolygon, the point it returns is within the largest (by area) sub-polygon. |
| [`random_number_between`](/docs/transforms/random_number_between.html) |   Returns a random float using a uniform distribution between the lower and upper values supplied: random_number_between(lower, upper) |
| [`random_number_normal`](/docs/transforms/random_number_normal.html) |   Returns a random float using a normal distribution with the mean and variance supplied: random_number_normal(mean, variance) |
| [`regex_capture`](/docs/transforms/regex_capture.html) |   function to capture a piece of text based on a regular expression |
| [`regex_named_capture`](/docs/transforms/regex_named_capture.html) |   capture a piece of text based on a regular expression |
| [`regex_replace`](/docs/transforms/regex_replace.html) |   function to replace a piece of text based on a regular expression |
| [`region_code`](/docs/transforms/region_code.html) |   Turn a point into the ID of a region, based on which region the point falls within. For example, if this dataset can produce |
| [`region_code_label`](/docs/transforms/region_code_label.html) |   Identical to region_code, but returns a text value. |
| [`repair_geometry`](/docs/transforms/repair_geometry.html) |   Attempt to repair the geometry. |
| [`replace`](/docs/transforms/replace.html) |   replace text with another piece of text |
| [`replace_first`](/docs/transforms/replace_first.html) |   replace the first occurrence of a piece of text with another piece of text |
| [`reproject`](/docs/transforms/reproject.html) |   reproject a geometry from one projection to another. |
| [`reproject_to_wgs84`](/docs/transforms/reproject_to_wgs84.html) |   function to reproject a geometry to WGS84. This will allow the geometry |
| [`right_pad`](/docs/transforms/right_pad.html) |   Pad `text` with the minimum number of copies of `pad` to reach `desired_length`. |
| [`round`](/docs/transforms/round.html) |   Round a number to a given precision. Trailing zeros are removed by default. Negative precisions round numbers to the left of the decimal. |
| [`set_projection`](/docs/transforms/set_projection.html) |   function to explicitly set the projection value on geometries which do not have projection |
| [`simplify`](/docs/transforms/simplify.html) |   Returns a simplified version of the Line, Polygon, MultiLine, or MultiPolygon using |
| [`simplify_preserve_topology`](/docs/transforms/simplify_preserve_topology.html) |   Returns a simplified version of the Line, Polygon, MultiLine, or MultiPolygon using |
| [`slice`](/docs/transforms/slice.html) |   Get a substring of a specified length of a text from a start index |
| [`source_created_at`](/docs/transforms/source_created_at.html) |   Get the fixed timestamp that this data source was created (ie: started uploading or importing). |
| [`split_select`](/docs/transforms/split_select.html) |   function to split a piece of text on a token, and then select |
| [`starts_with`](/docs/transforms/starts_with.html) |   tell whether or a not a string is prefixed with another string |
| [`state_boundary`](/docs/transforms/state_boundary.html) |   returns the boundary of the US state |
| [`title_case`](/docs/transforms/title_case.html) |   Make string title case with the exception of small words as defined by NYT Style Guide: |
| [`to_boolean`](/docs/transforms/to_boolean.html) |   cast a value to a true or false |
| [`to_checkbox`](/docs/transforms/to_checkbox.html) | No documentation is available. |
| [`to_fixed_timestamp`](/docs/transforms/to_fixed_timestamp.html) |   Turn a text value into a datetime with a fixed timezone. |
| [`to_floating_timestamp`](/docs/transforms/to_floating_timestamp.html) |   Turn a text value into a floating datetime. "Floating" means the timezone |
| [`to_json`](/docs/transforms/to_json.html) |   cast a text value to json |
| [`to_line`](/docs/transforms/to_line.html) |   parse a WKT (text) representation of a line into a line value |
| [`to_location`](/docs/transforms/to_location.html) |   This function has been deprecated. Please use the to_point function instead. |
| [`to_multiline`](/docs/transforms/to_multiline.html) |   convert a line into a multiline |
| [`to_multipoint`](/docs/transforms/to_multipoint.html) |   convert a point into a multipoint |
| [`to_multipolygon`](/docs/transforms/to_multipolygon.html) |   convert a polygon into a multipolygon |
| [`to_number`](/docs/transforms/to_number.html) |   cast a value to a number |
| [`to_point`](/docs/transforms/to_point.html) |   parse a WKT (text) representation of a point into a point value |
| [`to_polygon`](/docs/transforms/to_polygon.html) |   parse a WKT (text) representation of a polygon into a polygon value |
| [`to_text`](/docs/transforms/to_text.html) | No documentation is available. |
| [`to_url`](/docs/transforms/to_url.html) | No documentation is available. |
| [`trim`](/docs/transforms/trim.html) |   trim characters off the start and end of a string |
| [`trim_leading`](/docs/transforms/trim_leading.html) |   trim characters off the start of a string |
| [`trim_trailing`](/docs/transforms/trim_trailing.html) |   trim characters off the end of a string |
| [`upper`](/docs/transforms/upper.html) |   uppercase a string |
| [`uri_parse`](/docs/transforms/uri_parse.html) |   Parse a URI. |
| [`url_decode`](/docs/transforms/url_decode.html) |   URL Decode a value |
| [`url_description`](/docs/transforms/url_description.html) |   Extract the description part of a link. |
| [`url_encode`](/docs/transforms/url_encode.html) |   URL Encode a value. |
| [`url_url`](/docs/transforms/url_url.html) |   Extract the url part of a link. |
| [`validate_geometry`](/docs/transforms/validate_geometry.html) |   Test that the geometry is valid. |
| [`xml_pluck`](/docs/transforms/xml_pluck.html) |   Pluck a value out of an XML string using XPath. The returned value will be a string. |
