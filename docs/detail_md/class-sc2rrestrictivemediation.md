_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---





    


## Class sc2r:RestrictiveMediation


#### Tree


* [sc2r:MediationMeasures](class-sc2rmediationmeasures.md)

    * sc2r:RestrictiveMediation





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#RestrictiveMediation

#### Description
Restrictive mediation are a set of rules and limits that are placed on individuals to minimize the negative impacts in use of cyber resources.



#### Inherits from (3)

- [sc2r:MediationMeasures](class-sc2rmediationmeasures.md)

- [sc2r:PrepareMeasure](class-sc2rpreparemeasure.md)

- [sc2r:Response](class-sc2rresponse.md)





#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:RestrictiveMediation a owl:Class ;
    rdfs:label "Restrictive Mediation" ;
    rdfs:comment "Restrictive mediation are a set of rules and limits that are placed on individuals to minimize the negative impacts in use of cyber resources." ;
    rdfs:subClassOf sc2r:MediationMeasures .


```




#### Instances of sc2r:RestrictiveMediation can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="sc2r:RestrictiveMediation" href="class-sc2rrestrictivemediation.md" class="rdfclass">sc2r:RestrictiveMediation</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="sc2r:Response" href="class-sc2rresponse.md" class="rdfclass">sc2r:Response</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:mitigates" href="prop-sc2rmitigates.md">sc2r:mitigates</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Threat" href="class-sc2rthreat.md" class="rdfclass">sc2r:Threat</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:reduces" href="prop-sc2rreduces.md">sc2r:reduces</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Vulnerability" href="class-sc2rvulnerability.md" class="rdfclass">sc2r:Vulnerability</a>

                    
                    
                </td>
            </tr>

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="owl:Thing" href="class-owlthing.md" class="rdfclass">owl:Thing</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc1:creator" href="prop-dc1creator.md">dc1:creator</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc1:description" href="prop-dc1description.md">dc1:description</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc1:rights" href="prop-dc1rights.md">dc1:rights</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:creator" href="prop-dccreator.md">dc:creator</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:description" href="prop-dcdescription.md">dc:description</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:rights" href="prop-dcrights.md">dc:rights</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:hasID" href="prop-sc2rhasid.md">sc2r:hasID</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:relatesTo" href="prop-sc2rrelatesto.md">sc2r:relatesTo</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            

        

    

</table>













---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_
