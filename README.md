It is a simple ATM application which is used to perform specfic task like
                      changeAdminName
                      changeUserPassword
                      changeAdminPassword
                      checkBalance
                      newUser
                      depositAmount
                      withdrawAmount
                      
                      
                      
                      
                      
                      
Flow chart:

                                                                   
                                                  index                                              
                                                     |
                 -----------------------------------------------------------------------------------                                                                     
                |                                   |                                               |
                admin();                           user();                                           exit():
                  |                                |
                  |                                |               
                  |                                |               
                  |                                |               
                  |-changeAdminName();             |- changeUserPassword();                                  
                  |                                |               
                  |                                |               
                  |                                |               
                  |-changeAdminPassword();         |-checkBalance();                                      
                  |                                |               
                  |                                |               
                  |                                |               
                  |-newUser();                     |-depositAmount();                          
                  |                                |               
                  |                                |               
                  |                                |                         
                  |                                |-withdrawAmount();                 
                  |                                |               
                  |                                |               
                  |-exit();                        |-exit();                                                                    
                                                                                                
