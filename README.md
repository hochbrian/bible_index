# bible_index
Index of books of the Bible with Chapter and Verse Counts.

This is a simple project that just contains a JSON file with each book of the Bible listing out the chapters and the total verses in each chapter. This is useful for verification that chapter and verse references are valid, or for selecting a passage at random.


*Note: 3 John has 15 verses because I used the ESV to generate this. Some translations only have 14 verses in 3 John.


Format:

```javascript
Testament: [
	{
		"name": "name of book",
		"shortName": "useful for API calls",
		"chapterCount": [total chapters in book],
		"chapters": {
			"chapter": [total number of verses in chapter]
		}
	}
]

```
