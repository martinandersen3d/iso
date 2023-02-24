
# Iso Standards

Here is short explanations of the different ISO standards, used in Data Science and Software Development

# ISO 639-1 
[Wikipedia Link](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)

**Language** - This standard defines two-letter codes in lower-case for representing languages.


# ISO 3166-1 alpha-2
[Wikipedia Link](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)

**Country** - This standard defines two-letter codes in UPPER-CASE for representing countries.

# ISO 4217
[Wikipedia Link](https://en.wikipedia.org/wiki/ISO_4217)

**Currency** - ISO 4217 is the standard for currency codes. It defines three-letter codes (alphabetic code) for most currencies in the world. The codes are composed of the two-character ISO 3166-1 country code and a third letter for the currency. Here are some examples of ISO 4217 currency codes:

USD - United States Dollar
EUR - Euro
GBP - Great British Pound
JPY - Japanese Yen
AUD - Australian Dollar
CAD - Canadian Dollar

ISO 4217 also defines numeric codes for currencies, which consist of three digits that are used to identify currencies without reference to their names or symbols. The numeric codes are used in situations where a country's currency has no international symbol or when the symbol is not commonly used.

# ISO 8601
[Wikipedia Link](https://en.wikipedia.org/wiki/ISO_8601)

**Date Time** - ISO 8601 is the standard for date and time representation. It defines a format for representing dates and times in a way that is unambiguous and easily parseable by computer systems. The ISO 8601 format uses a combination of numbers and special characters to represent dates and times, and it includes options for specifying time zones and durations.

The basic format for representing dates in ISO 8601 is YYYY-MM-DD, where YYYY is the four-digit year, MM is the two-digit month, and DD is the two-digit day. The format for representing times is HH:MM:SS, where HH is the two-digit hour (in 24-hour format), MM is the two-digit minute, and SS is the two-digit second. Fractions of a second can also be included using the format .SSS.

ISO 8601 also includes a format for representing date and time together, which is YYYY-MM-DDTHH:MM:SS. The "T" in the middle separates the date and time components. Time zones can be included by appending a time zone offset to the end of the date and time, using the format +/-HH:MM. For example, the current date and time in the Eastern Time Zone of the United States could be represented in ISO 8601 format as 2023-02-23T14:25:30-05:00.


# Timezone
**ISO 8601** - This is a standard for date and time representation, and it includes a format for representing timezone offsets. The format is "+/-HH:mm" where "+" represents the timezone offset ahead of UTC and "-" represents the offset behind UTC. HH represents the number of hours in the offset, and mm represents the number of minutes in the offset. For example, the timezone offset for New York (Eastern Standard Time) would be "-05:00" during daylight saving time and "-04:00" during standard time.

**ISO 3166-2** - This is a standard for representing country subdivisions, including regions that may have their own timezone offset. Each subdivision has a code consisting of two parts: the ISO 3166-1 alpha-2 country code and a subdivision code. The subdivision code can include a numeric code for the timezone offset, such as "US-CA" for California, which is in the Pacific Time Zone (UTC-08:00 during standard time and UTC-07:00 during daylight saving time).

