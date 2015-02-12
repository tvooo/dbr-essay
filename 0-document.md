# Introduction

> nigel cross; products are published, but are not really accessible. from processes we have mostly proceedings, and other stuff from academia. could be better. what about learning more from people? people who designed the products..:!!!

The global pool of design knowledge is steadily growing. Both industry and academia contribute through design practice and structured design research. However, there is a large gap between the knowledge that is produced and the knowledge that is published. Most of the produced knowledge is never made accessible to the design community outside of the own organisation, less so in industry than in academia.

Not only is there an internal gap in design; there is also a difference between how much knowledge design and other disciplines make accessible (looking specifically at software development). According to @davis2009, “the proprietary behavior of design practitioners will not make new knowledge widely available […]”. This is an unfortunate circumstance, as several other disciplines show that both industry and academia would benefit from better access to existing knowledge.

In this essay, I present two examples from the areas of open source and open innovation, which successfully illustrate how open knowledge can contribute to innovation. I will further suggest ways forward for design towards more accessible design knowledge.

# Design knowledge publication

Much of the design knowledge in existence and production is never made widely available. This section looks at where design knowledge can be found, and how—if at all—it is made accessible to a wider community of designers. But where do we find design knowledge? Nigel Cross [-@cross2] suggests three sources: people, processes, and products.

*People*, especially—but not exclusively—designers, know about the decisions they made while designing. They bring their past experience and their world view to the design process, influencing the outcome with everything they do. Cross also claims that designing “is a natural human ability” [-@cross2]. An extensive account of how design practice and practitioner are working in accord is given by @schon1990.

*Processes* are the “tactics and strategies of designing” [@cross2]. Design knowledge in process resides in pattern libraries, design manifestos, and basically every method used to create and evaluate a design. It is made especially explicit if it is found in *byproducts* of the design process: in recorded interviews and user tests, in affinity diagrams and brainstorming sessions. It also becomes visible in the way we publish knowledge in academia: through magazines, journals, conferences and their proceedings.

Lastly, *products* are the most obvious outcome of design, “the forms and materials and finishes which embody design attributes” [@cross2]. The product is a product of decisions based on experience and evaluation. The product is *design decisions made explicit*.

Cross’s theory does not delimit design knowledge to reside solely within the design discipline; it also shows that design knowledge can be found way outside the traditional design discipline: in the people who make decisions about pricing and marketing, in governmental regulations, in the market, …

However, most of these instances of knowledge are not universally accessible. Accessibility depends on the *form* the knowledge takes, how it is published, and the other the designers’ ability and willingness to make sense of it. As @lowgren2013 points out, “it was the *video of the TED demo talk* on MTI […]—providing a fairly rich mediation of the artifact itself—that swept through the HCI worlds of academia and business like wildfire, *rather than the previously published academic papers* on the project.” (my italics). ^[See [http://www.ted.com/talks/jeff_han_demos_his_breakthrough_touchscreen.html](http://www.ted.com/talks/jeff_han_demos_his_breakthrough_touchscreen.html), accessed 29-01-2015]

To summarise, design communities traditionally communicate through the artefact itself [@gaver]—mediated if necessary. Academia publishes knowledge mainly in a written account, through journals and proceedings -> products and papers are the main things that reach other designers. But those are both highly polished forms of knowledge that make many facets not very explicit. I believe that research (wether it arises from practice or directed research programmes) needs to be published in a more raw form; a format more adequate for (re-)use by other designers—we do not want to reinvent the wheel.

Companies keep their design and development proprietary for quite obvious reasons. They want to be first to market, outperform competition, and satisfy shareholder expectations. They do this by means of non-disclosure agreements, patents and other intellectual property means. By not making the knowledge produced internally available—sometimes not even within the own organisation—other designers are not able to use it. This situation is unfortunate, as both the producer of knowledge and the general design community can benefit from sharing knowledge, as is shown by other disciplines. **there are examples where opening up the process leads to: innovation, trust, better products, quicker development**

# Open knowledge in other disciplines

Disciplines other than design have been quite successful in sharing knowledge across their communities. This section will present two occasions of open collaboration in engineering: *open source software* development and *open patent pools*.

## Open source software

*Eclipse* is a modular, general-purpose *integrated development  environment*—a computer program made for creating software. Originally developed as a proprietary product and heavily funded by IBM, it was later released under an open source license and pledged to the Eclipse Foundation, which was founded to maintain Eclipse and the ecosystem around it with respect to stakeholder interests. The Eclipse Foundation is “a consortium of major software vendors, solution providers, corporations, educational and research institutions and individuals working together” [@eclipse].

Eclipse is open source software, which means that anyone can use it, view its source code, make adjustments, and contribute back to the project. Through open governance and development, the foundation fosters transparency: “Project discussions, minutes, deliberations, project plans, plans for new features, and other artifacts are open, public, and easily accessible.” [@eclipse] Similar approaches are applied by the Linux Foundation, the Apache Foundation, the Mozilla Foundation, and others.

One can see a clear parallel between the Eclipse Foundation’s model of collaboration and a design research programme: a space for companies and institutions with shared interests to work together on a (mostly) common goal. But making this point is not my intention. Instead, I would like to look at the position and behaviour of single companies and institutions within the foundation: they contribute their engineers’ time and expertise to improve a product that benefits not only themselves, *but also their competitors*.

For companies creating software based on Eclipse, the benefits are numerous: the collaboration reduces risks, as the sustainability of the technology is ensured by many stakeholders; companies can save time to market and reduce their development costs, as a product can be built on top of the existing platform; common standards are defined and a higher rate of standards adoption is achieved; and a great pool of professionals with relevant skills in the technology is available for hire.

From a competitive-economic point of view, however, a collaboration like this seems counterintuitive: why would a company contribute to the success of its competitors? Many OSS projects like Eclipse, Linux, Java, OpenOffice, or MySQL show that sharing knowledge (e.g. through code) does not eliminate competitiveness. According to @eclipse, the competition is just moved to a different level: “Compete on products, collaborate on the platform”. Technology is not a factor of differentiation anymore—the value is created on a product level instead. At the same time, companies using Eclipse benefit from a technology that is far more developed than it would be if it was developed in a proprietary manner.

Vendors now create “complementary products, services and capabilities” on top of the Eclipse platform [@eclipse]. IBM has whole product lines based on the Eclipse platform, including end-user groupware client *Lotus Notes* and the software development tools of the *Rational* family. The official Android SDK by Google is built upon Eclipse. And many smaller companies offer commercial support and training for development using Eclipse.

## Open patent pools

In the development of new products, patents often play an important role. They are necessary to protect inventors, but they can also prevent innovation and progress—the patent wars between mobile phone and operating system vendors are a contemporary example.^[See [https://en.wikipedia.org/wiki/Smartphone_patent_wars](https://en.wikipedia.org/wiki/Smartphone_patent_wars), accessed 11-02-2015]

Several organisations and patent pools—consortia that cross-license their patents to their members—exist to protect certain communities instead of single companies and their interests. They open their patents to the public for royalty-free use.

One such organisation is the WebM Project^[See [http://www.webmproject.org/](http://www.webmproject.org/), accessed 10-02-2015], which manages and develops the open WebM container format for videos. It is the main effort, supported by several web browser vendors, to use VP8 as the video format for HTML5. VP8 is a video compression technology owned by Google, but Google irrevocably released its patents and published the format specification under an open license. The goal of Google and other browser vendors within the WebM project is to create an interoperable standard for video technology on the web—no matter if the user is on Firefox, Chrome, Internet Explorer or a different browser.

Several more examples exist: The Open Invention Network is “a shared defensive patent pool with the mission to protect Linux”.^[See [http://www.openinventionnetwork.com/](http://www.openinventionnetwork.com/), accessed 11-02-2015]

Quirky is an innovation company that helps makers and inventors to put their product ideas to market. In a collaboration with General Electric (GE), Quirky created what they call “inspiration platform”^[See [http://inspire.quirky.com/](http://inspire.quirky.com/), accessed 08-02-2015]

However, the inspiration platform has received critique from makers and open source enthusiasts alike, as the patents are not reeeeaally open, and quirky forces their users into a weird license [@quirky].


@patenting put forward a framework for companies to pledge patents to the public, in order to foster innovation.

As can be seen, patents—which are a representation of an inventor’s knowledge—can not only be shared for profit, but also for the protection of thriving communities of innovation—for the benefit of a wider audience.

# Ways forward

All those examples came from technology - is it easier than design?

It seems impossible to find similar projects in the design industry. While R&D in development seems to recognise the benefits of collaboration and knowledge sharing, design research and practice is still taking place mostly in a solitary way.



Much of the example above is about politics: structure to protect and/or liberate intellectual property, such as foundations, licenses, and patents. but the oss stuff also involves a lot of non-political, very direct involvement of people with publishing knowledge.

Design seems to lack such examples as we have seen from software development (The Eclipse Foundation) and engineering (GE).

We should make use of open, interoperable standards (such as provided by ANSI, ISO, DIN, IEEE, IETF and so forth) as opposed to proprietary standards. We can release patents to the public, using a framework as was suggested by @patenting.

All those activities are not specific to the design discipline at all, and companies are already following them. But most of these knowledge pieces describe the *what* rather than the *why*.

**How can DESIGN do this? Specific to design**

If we look at the open source software community, we can find an example of the creation and distribution of knowledge that happens in a very *natural* way.

**dvs, commit messages are annotations/explanations/documentation, diffs are precise documentation**

Open source processes are native to the discipline of software engineering. Developers document their work by creating self-explanatory code, accompanied by comments and API documentation. They have found a way to make their knowledge about the code obvious to other, properly trained developers. One of the main focus for program code nowadays is to be reusable—an attitude that we do not see in the design industry.

Design is a different discipline from software engineering, with different traditions and practices. But I believe that we can find ways of publishing knowledge in a natural, effortless manner that can easily be integrate into our existing design and research practice. The following are thoughts on how to do this.

We can document the design process publicly. Many companies, design agencies and designers already do this, in the form of blog posts^[See [http://bradfrost.com/blog/post/techcrunch/](http://bradfrost.com/blog/post/techcrunch/) for an example (accessed 09-02-2015)] or by describing their typical design process as a USP^[See [https://teamgaslight.com/process](https://teamgaslight.com/process) for an example (accessed 09-02-2015)]. But these are efforts that do not provide too much detail, and are also quite ‘artificial’—in the sense that those pieces of knowledge do not originate in the design practice itself. I believe that we can publish design knowledge in a way that is natural to the discipline, in ways that are integrated into our design practice.

**Publishing non-critical internal documents**

I can imagine to publish byproducts of the design process—such as flow charts, affinity diagrams, and interview recordings—using appropriate representations of intermediate-level knowledge [@lowgren2013]. Such a representation could be an annotated portfolio, as suggested by @gaver, or **bla bla bla** as put forward by @pierce.

In OSS and patenting, we have seen the concept of a foundation to work quite well in providing protection and liberty for knowledge at the same time.

# Conclusion

Design, as a discipline and an industry, can learn much from movements such as *open source* and *open innovation*. While software engineering is arguably, due to the very immaterial and digital nature of it, predestined and privileged to be taking place in the open, design practice often has material and informal components which are difficult to document in-the-moment. However, we can make use of existing, easy to create representations of knowledge that we share with the design community. Other disciplines show that sharing enables innovation and does not endanger competitiveness.