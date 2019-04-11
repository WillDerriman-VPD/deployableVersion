#Deployable Version


## Critical Formulae

### Reco

__Phase__ 

=if(C2="Phase Name",A1+1,A1)

__Task__

=if(C2="Phase Name",0,if(H2="",B1,if(H1="",B1+1,B1)))

### Testing

__Phase__

=if(C3="Task",A2+1,if(A2="",0,A2))

__Task__

=if(C3="Task",0,if(C3="Name",B2+1,B2))