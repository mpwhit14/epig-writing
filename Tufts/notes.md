##Notes

Points to make:

1.  How my editing is done
2.  Things I have added on that are not just editorial
      - Digital editions can be worked with in **more** ways than print editions
      - Concepts and topics tree
      - Geographical data
      - Character data
      - Allows for viewing the texts in different contexts
3.  How do we organize and structure an archive for multiple kinds of use/reuse?
      - Multipurpose
      - My archive is open to automated analysis but also handcrafted essays (since it is citeable)
      - Textbook vocab?  Morphological analysis?

My name is Megan Whitacre and I am a senior at the College of the Holy Cross.  My personal project, Latin Epigraphy and Pedagogy, aims to create a tool to bring epigraphy into the classroom, particularly a first-year classroom.  My work has involved essentially the same editorial process with an entirely different kind of material - Latin inscriptions.  Like the other projects, my material is transcribed in an XML document.  However, in order to make the material more adaptable especially from a pedagogical perspective, I have added a few other layers of analysis.

Since I want my material to be useful for teachers, I wanted a way to organize and search through the material based on things you might teach in a classroom.  I began by creating a set of URNs for individual grammatical topics, such as the perfect active indicative verb form, and I grouped these topics under another set of URNs for larger concepts.  Then, I was able to cite sections of images that illustrated those topics and concepts and link them in an RDF graph.  As a result, I have created something like a web of relationships between concepts and topics and images of instances in real Latin.  It looks like this:  (**visualization**).  As you can see, the purple axis is the concepts, which is linked to the orange axis and blue axis, verbal and noun topics, and those are linked to the images.  If we start **HERE** then we can go **HERE** and then see an image that illustrates that **HERE**.  Or, alternatively, we could start at an image and see all the grammatical "tags", like **HERE**.  

Within the XML documents, I have also been identifying characters and geographical data, as you can see **HERE** (**screengrab**).  Now, I have indices of grammatical concepts and more specific concepts, and indices of characters and places mentioned in these inscriptions.  All of these things are relationships in the RDF graph, so they are relationships connected to even more relationships, all of which are searchable and sortable.  

From a teacher's perspective, this means the epigraphic material is more than just a print textbook - it is dynamic and easily adapted to fit the needs of the user.  For example, a teacher could use the grammatical concepts and topics to find inscriptions that illustrate what their lesson is about, or pull out all the inscriptions that mention a particular character, such as the emperor Vespasian, or focus on inscriptions that specifically mention the city of Rome, et cetera. In addition, when the XML documents of the transcribed texts are run through morphological analysis, they can be identified down to a specific word.  So, if a teacher has a list of vocabulary, like **this**, he can even find inscriptions that contain words his students will already be familiar with.  For example, **THIS**

Likewise, the organization and editing on this project allows for automated analysis across a large body of work - something that is especially important in projects like the Homer Multi-text, where they are looking at several versions of huge manuscripts.  However, this kind of automated analysis can also provide data useful to a teacher, who would be able to look at the statistics for how often a oertain concept appears in this body of material, and restructure his or her curriculum based on that data.

As with all the projects we have talked about, the XML editing and the RDF relationships allow for automated analysis but also are completely citeable, so any handcrafted essays can be linked directly to the visual evidence.  The material is dynamic - it can be viewed from a variety of different angles and more relationships can be added.  The web of relationships that has been created allows us to look at the material in a multitude of different contexts - it is multipurpose and adaptable in ways that print texts simply cannot be.
