CryptoMood - Data Engineering Interview Question
================================================
.. header:: Invitae - Confidential
.. |date| date::

:Date: |date|
:Author: Pavel Katsev <pavel.katsev@invitae.com>

This project prototypes a system for monitoring crypto currency prices and sentiment of Twitter messages surrounding the coins of interest.
It is meant to be a homework exercise for Data Engineers interviewing at Invitae.
We hope that our candidates will ask questions and treat this exercise as a chance to collaborate with Invitae's team prior to joining.

Tasks
-----
The immediate objective is to enable one core feature:

* Historical correlation view of sentiment to price.

Historical Correlation
~~~~~~~~~~~~~~~~~~~~~~
Goal: Perform a correlation analysis on the historical sentiment and price data.

Use the provided data files to perform a correlation between cryptocurrency price and twitter sentiment.  It should utilize
the data in ``historical_coin_data.txt`` and ``historical_sentiment_data.txt`` to build the correlation.

Deliverables
~~~~~~~~~~~~
Either working code that takes this project to the "next level" or well-documented technical discussion of what work should be done.

Bonus Discussion Points:
~~~~~~~~~~~~~~~~~~~~~~~~
* High-level discussion of architecture for productionizing this project. Consider the following:

  * moving to a real-time streaming architecture instead of batch based

Contents
--------
The API consumer scipts:

* ``historical_sentiment_data.txt`` - a file containing twitter post sentiments
* ``historical_coin_data.txt`` - a file containing trade information (market prices)
