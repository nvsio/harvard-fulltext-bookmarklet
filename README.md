### harvard-fulltext-bookmarklet
---

#### **General**
JavaScript bookmarklet to simplify the processes of having to append '.ezp-prod1.hul.harvard.edu' between URLs needing Harvard Site licensing (e.g. PubMed full text).

#### **Install**
Visit [nikhilsrinivasan.github.com/harvard-fulltext-bookmarklet](nikhilsrinivasan.github.com/harvard-fulltext-bookmarklet) to find the pre-compiled bookmarklet, ready for drag and drop. Otherwise compile the bookmarklet manually by following these steps:

1. Copy the following javascript code: javascript:location.assign(location.protocol+'//'+location.hostname+'.ezp-prod1.hul.harvard.edu'+location.pathname+location.search+location.hash);

2. Navigate to your browser's bookmarking utility and create a new bookmark, pasting the copied javascript code in the URL field. Name the bookmark appropriately and optionally place in the bookmark bar for convenient access.

3. Success; your bookmarklet should now run a JavaScript that will append '.ezp-prod1.hul.harvard.edu' between URLs needing Harvard Site licensing. Test it out at http://www.ncbi.nlm.nih.gov/pubmed/!

#### **Usage**
After saving the bookmarklet to the browser being used, when visiting a webpage needing Harvard PIN authentication, simply click on the bookmarklet to append the '.ezp-prod1.hul.harvard.edu' path to the URL and redirect you to the right page. This will redirect you through the Harvard PIN authentication if necessary.

#### **Acknowledgements**
* [@gruber](twitter.com/gruber) for his bookmarklet formatting [script](http://daringfireball.net/2007/03/javascript_bookmarklet_builder)
* [@mdo](twitter.com/mdo) and [@fat](twitter.com/fat) for their contributions to the Twitter Bootstrap framework

#### **License**
Copyright (c) 2013 [Nikhil Srinivasan](https://github.com/nikhilsrinivasan). Licensed under the [MIT License](https://github.com/nikhilsrinivasan/harvard-fulltext-bookmarklet/blob/master/LICENSE).