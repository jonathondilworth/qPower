*Authors Note: This is a very loose initial version of (what I hope will become) a finalised research paper. I have a real world application for this research; and although the defined goals may vary over time, they will be iterated over. Right now, I can identify what I require and generate a set of hypotheses'.*

### Loose Notes

**Research Project Title:** Identifying and Indexing Quotes from a Variety of Text Based Mediums

### Objectives (Scope -> Inf)

* Reliable Quote Extraction from **ANY** Piece of Text
	* Extraction from a simple piece of unformatted piece of text
	* Extraction from a piece of formatted text
	* Extraction from an RSS or News feed
	* Extraction from a web page
	* Extraction from a PDF document
	* Extraction from a piece of scanned paper containing only text
	* Extraction from a piece of scanned paper containing unknown content
* Attributing Extracted Quotes to an Author (possibly multiple)
* Attributing Extracted Quotes to a Date and Time (possibly multiple)
* Attributing Extracted Quotes to a Source (possibily multiple)
* Assigning a Scalar Value to each Quote Representative of:
	* General Confidence: The Quote = A Quote, Author = An Author, etc - essentially:
	```
	def func reliability_of_identity(mediums, author, dates, times, sources):
		return absolute_value_slash_percentage_of_quote_confidence
	```
* Classifying Authors (Groupings Such As: Academic, Blogger, Mainstream News Reporter, Youtuber, Influencer, etc)
* Identify Pairs: {Quote: [Authors, ...]}
* Identify Original Author & Confidence Value: {Quote: [Original_Author, Confidence]}
* Identify Author Credibility
* Identify If Similar Quotes Exist (Word Vectors?)
* The Number of Estimated Instances Where Similar Quotes Were Found (ALLOW NULL)

**This Project Is WAY TOO BIG. Slowly double diamond over time, when you have time.**