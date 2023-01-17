# Shutting down data capture

On 2022-12-10, Texas stopped allowing access to https://dshs.texas.gov/immunize/covid19/COVID-19-Vaccine-Data-by-County.xls and instead returned an xls file with the phrase "Redirecting to https://dshs.texas.gov/covid-19-coronavirus-disease-2019/covid-19-vaccine-information." in cell A1.

On 2022-12-16, Texas changed this to a HTTP 301 response (moved permanently) *without* a location.  The body of the response indicates "The document has moved <a href="https://www.dshs.texas.gov/immunize/covid19/COVID-19-Vaccine-Data-by-County.xls">here</a>.</p>" however this url redirects texas hhs site.

There appear to be other ways to scrap this data and Texas may be properly reporting their vaccination data to the federal government, now.  I'm no longer on a an active project modelling the spread of COVID-19.

I'll leave this repository up for historical purposes and if you are using it or have any questions.  Contact me at mr.patfarrell at symbol gmail dot com.
