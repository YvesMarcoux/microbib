---
DC.creator: Yves MARCOUX
lang: fr-CA
title: Commentaires, suggestions, questions d'Yves
viewport: width=device-width, initial-scale=1.0
---

# Commentaires, suggestions, questions d'Yves

Yves Marcoux -- mars 2026

Ce document est l'outil de communication par lequel je compte formuler
commentaires, suggestions et questions à l'intention des équipes Stylo
et Métopes dans le cadre du projet de conversion des articles Stylo en
articles MétopesCommonPublishing.

Vous êtes invités à prendre connaissance de tous les items et à y
réagir, même s'ils ne vous sont pas directement adressés.

Pour me répondre ou ajouter des commentaires, le mieux est d'utiliser le
fil de discussion github associé au présent document. Vous pouvez aussi
le faire par courriel
[`ymarcoux@gmail.com`](mailto:ymarcoux@gmail.com?subject=Stylo-Métopes).

------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  No         Date         Pour\      Type         Objet                Date\        Réglé ?
                          qui ?                                        réponse      
  ---------- ------------ ---------- ------------ -------------------- ------------ ------------------------------------------------------------------------------------------------------------------------------
  1          2026-02-27   stylo      suggestion   ~~À côté des noms de 2026-02-27   oui, intégré à l'[article
                                     -- codage MD classe \"question\"               martyr](https://github.com/gromettoclara/StyloMetopes/blob/d6b73e8b2958d9b958126d5a1cb2469a537e375a/martyr/mkdnreference.md)
                                                  et \"speaker\", le                
                                                  \"answ\" fait figure              
                                                  de parent pauvre et               
                                                  je suggère le mot                 
                                                  complet                           
                                                  \"answer\".~~                     

  2          2026-02-28   stylo      suggestion   Les lignes 232 à 237              
                                     -- codage MD du MD (la toute fin)              
                                                  sont inutiles, il                 
                                                  faudrait les                      
                                                  retirer. `pandoc`                 
                                                  met *toujours* la                 
                                                  bibliographie dans                
                                                  une division bien                 
                                                  identifiée. La                    
                                                  marquer                           
                                                  explicitement ne                  
                                                  sert que si on veut               
                                                  l'avoir ailleurs                  
                                                  qu'à la fin. Dans la              
                                                  conversion vers                   
                                                  Métopes, la                       
                                                  bibliographie est de              
                                                  toute façon déplacée              
                                                  par la                            
                                                  transformation XSLT,              
                                                  puisqu'elle doit se               
                                                  retrouver en                      
                                                  \<back\>. Il est                  
                                                  donc normal que le                
                                                  MD se termine par le              
                                                  titre que l'on                    
                                                  souhaite donner à la              
                                                  bibliographie : la                
                                                  XSLT va le déplacer,              
                                                  tout comme la                     
                                                  bibliographie                     
                                                  elle-même, en                     
                                                  \<back\>. J'ai aussi              
                                                  fait en sorte que si              
                                                  le MD ne se termine               
                                                  *pas* par un titre                
                                                  de bibliographie (ce              
                                                  qui est le cas en ce              
                                                  moment, puisqu'il y               
                                                  a un paragraphe                   
                                                  après le titre),                  
                                                  alors la XSLT va                  
                                                  elle-même injecter                
                                                  le titre                          
                                                  \"Bibliographie\"                 
                                                  (ou \"Bibliography\"              
                                                  si l'article n'est                
                                                  pas en français).                 
                                                  C'est pour ça que tu              
                                                  peux voir dans                    
                                                  l'extrant Métopes                 
                                                  actuel le titre                   
                                                  \"Bibliographie\".                

                                                                                    

                                                                                    
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------
