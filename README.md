# Exploring Bavarian results of the EU election 2024 open data with Jayvee
The EU publishes large amounts of open data. They re-use their own open data to allow citizens to gain insights into the EU elections 2024 (see, for example, [these news](https://data.europa.eu/en/news-events/news/eu-election-results-are-here-learn-how-votes-are-distributed)).

Based on published open data, citizens can run their own analysis. Sadly, the published data is not easy to use. With Jayvee, we can easily model a data pipeline that allows us to extract, clean and transform data and finally save it in a SQLite database for further use. You can find more information about Jayvee at [https://jvalue.com/](https://jvalue.com/) and on GitHub at [https://github.com/jvalue/jayvee](https://github.com/jvalue/jayvee), here we use version 0.5.0.

You can find an example analysis in the [report.ipynb](report.ipynb). The Jayvee model used can be seen in [eu-elections.jv](eu-elections.jv).