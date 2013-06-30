####Tracing cooperative work through scholarly paratexts, a pilot study of Bioinformatics        

<br>
        
#####Abstract
Information science has traditionally looked at the journal article as an artifact of scholarly work, using elements like authorship, or citation lists to trace meaningful connections between idnividuals, locales or subjects. Here, we build off of previous works that have used the acknowledgment statements found in published journal articles as a way of understanding the collaborative nature of bioinformatics as a cooperative discipline that developes software and information systems to enable new discoveries to be made. We discuss implications for the study of cooperative work more generally, and provide some preliminary results from a pilot study of bioinformatics as an exemplar of the software-intensive engineering discipline. 

#####Introduction
Our aim here is to bring an information science tradition of scientometrics to the study of 
cooperative work. We are particular interested in traces and evidence of cooperative work that can be mined from publications from domains where software and information systems are developed, as well as workplace settings where traditional science questions are approached by groups that collaborate using cyberinfrastructures. 

#####Background
The field of computer supported cooperative work (CSCW) is concerned largely with the way that people design, build, use and manipulate technologies to achieve a shared task or desired outcome. These studies are often aimed at understanding how the emergent properties of a collaborative technology effect collaboration (), or how the design of a particular application can be of used to ease the burden of working at different times, or in different geographical places  (). Methodological approaches to studying cooperative work tend to be of two very distinct flavors: 1. qualitative, field based observations and 2. quantitative data analysis of either a technology or a group's task-based performance. 

The more informal qualitative approach is an in-situ study. This type of scholarship often relies on ethnographic or contextual inquiry methods which allow the researcher, through narrative reconstruction, to reflect upon the practices of a technology and it's users "as it happens". Implying that these methods capture the dynamics of a workplace that are rapidly and dynamically changing.

Conversely, the more formal quantitative methods of CSCW use an ex-situ approach. oftentimes these take on a flavor of post-hoc analysis by assembling traces of a user's activities or communications from a collaborative system in order to either critique an existing design and suggest improvements, or to demonstrate the effects of some sort or design-based intervention for inducing more favorable behaviors ( a recent example is Mueller, 2012). 

Information science has much to offer the field of CSCW, including its rich history of metric based analysis of collaboration, co-production (authorship, bibliographic coupling, etc) and network analysis. However, CSCW rarely considers scholarly publications, or formally published literature as a data source for investigating cooperative work. There are a number of reasons for this omission; the publication of research article are slow, citations take many years to accumulate and can't be relied upon for design interventions; journal articles and books tend to be authored by a few elite members of a research group that cite other elite members- in order to understand a technology in use, or a potential improvement of a collaborative arrangement it is often necessary to study those that are not a part of this elite class of authors, and are often invisible to such rationalized models of authorship (Suchman, 2007).

These are all relevant critiques and limitations of using publications, and formal scholarly products as a data source for CSCW study. Here, we suggest a way to use scientometric techniques as a methodological bridge between the quantitative and qualitative divide of CSCW research. We believe there is much to be gained by more informed in-situ studies, and quick and dirty ex-situ - and that 
 
{why does this matter to Information Science}  <--- It has to be a vice versa- there is much to be gained by both sides.  
 
The formally published literature represents, as Sharon Traweek put it, the ledger of science - who made what claim when. 


#####Methods

[should discuss the symmetry of our method and those of bioinformatics -- the field has largely embraced a computational appraoch to inquiry, leveraging the increased power of multi-core processors to ask new questions about biological systems that were difficult, if not impossible to operationalize in laboratory setting.] 

Our own methods draw upon previous work -- most heavily on Cronin, Shaw and Labarre (2004) -- in constructing a classification of acknowledgement types. However our operationalization of this study diverges greatly. We took advantage of increased access to texts via full content API's and used text-mining algorithms to extract a sample size, which by previous analogue standards would seem unthinkable (n=250 out of a corpus of approx 9741). <--- does that seem like enough?  appropriately unthinkable?    

Together, both authors coded a sample of acknowledgement sections from the journal _Bioinformatics_ to according to Cronin, Shaw and LaBarre's 2004 classification scheme, noting cases where the classification scheme could be expanded to highlight computational contributions to scholarhip in a more detailed manner.  Both authors then separately coded a second sample set of acknowledgment sections, and compared the resulting codes to further refine our codelist.  Our final codelist follows:
<br>
**Financial** (unchanged)
<br>**Moral** (unchanged)
<br>**Editorial** (unchanged)
<br>**Conceptual**  (includes help with research design, software design, "helpful discussions," and other contributions to the conceptual framework of the project. altered from Cronin; described in more detail below)
- statistical/mathematical
- software design
<br>**Material/Instrumental** (expanded from Cronin; described in more detail below)
- providing access to data
- computing access/facilities
<br>**Technical** (expanded from Cronin; described in more detail below)
- technical instruction (software/hardware)
- software/hardware implementation
- debugging/refactoring
<br>**Unknown**

This codelist parts from Cronin, Shaw and LaBarre's classification scheme in several key ways:
- We consider statistical/mathematical assistance a conceptual contribution.  We additionally consider software design a conceptual contribution; in many cases software is a primary research output in bioinformatics.
- We split Instrumental contributions from Technical contributions; Instrumental contributions also consist of "Material" contributions that range from computation facilities to the provision of finite resources like reagants and other chemical compounds
- We specifically noted acknowledgement of data providers and computational facilities as subcategories under the Instrumental/Material category
- We specifically note several different kinds of technical support.

Finally, the authors separately coded a final sample set of acknowledgement sections (n=200) according to this more refined scheme, and compared classifications to assess intercoder reliabilty (presented below).

#####Results

#####Discussion/Conclusions

Why do we do this and what are the known problems with this?
We feel these more nuanced categories will support our goal of making technical contributions more visible. Additionally, we note that technical contributions can be particularly difficult to 

