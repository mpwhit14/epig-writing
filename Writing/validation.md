##How do I recognize and verify adequate work?

This project is made up of two big components that are prone to mistakes:  the edited texts and the images tagged by grammatical topic.  I would like a system to check these two components against one another in order to find discrepancies and mistakes.

First, the text inscriptions must be tokenized, so that they can be verified with a program like the MOM system used in the Homer Multitext project.  Then, when the text can be cited down to the word, I would like to connect each word to the specific section of image that illustrates that word, via the RDF graph.  The sections of image should already be identified and related to a grammatical topic.

At this point, a syntactic analysis of the text is needed.  I would like to be able to determine the grammatical topic that should be related to each word in the text.  That is, each word in the text should be automatically related to the grammatical topics that it illustrates.

In this way, the text of each inscription will be verified automatically, and from there, the further relations in the graph will be validated.  If each tokenized word in the text is connected to particular grammatical topics, and the images of each word are connected to certain grammatical topics, we would know that the image has been identified correctly when the topics match.  This will verify the accuracy of the images and the topics related to the images.  

The question remains: is it possible to automatically determine the syntax of a Latin inscription?  There are many problems with this, particularly since the inscriptions we are working with are not "proper" Latin sentences and are littered with abbreviations and varations in spelling.  How does one parse a Latin word in any way other than personally looking at it?
