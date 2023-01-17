# Shutting down data capture

On 2022-12-10, Texas stopped allowing access to https://dshs.texas.gov/immunize/covid19/COVID-19-Vaccine-Data-by-County.xls and instead returned an xls file with the phrase "Redirecting to https://dshs.texas.gov/covid-19-coronavirus-disease-2019/covid-19-vaccine-information." in cell A1.

On 2022-12-16, Texas changed this to a HTTP 301 response (moved permanently) *without* a location.  The body of the response indicates "The document has moved here(https://www.dshs.texas.gov/immunize/covid19/COVID-19-Vaccine-Data-by-County.xls) however this url redirects texas dshs site which doesn't provide links to the data any more.

There appear to be other ways to scrap this county level vaccination data and Texas now may be properly reporting their vaccination data to the federal government.  I'm no longer on a an active project modelling the spread of COVID-19, so I'm not tracking this directly.

I'll leave this repository up for historical purposes and if you are using it or have any questions.  Contact me at mr.patfarrell at symbol gmail dot com.


Update 2023-01-17:  After a bit of digging, I found the location Texas moved the file to, no thanks to their website or http status information.  It looks like they are publishing data on Wednesdays now, so I've adjusted the capture to reflect that.
