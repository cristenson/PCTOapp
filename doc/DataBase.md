# DataBase
## Anagrafica
- TipoAzienda
- RagioneSociale PK
- Comune
- CAP
- Via 
- Settore 

## Progetti
- ID auto_increment PK
- RagSoc --> FK in Anagrafica(RagioneSociale)
- Classe 
- NomeProgetto
- DescrizioneProgetto

## Contatti
- ID auto_increment PK
- RagSoc --> FK in Anagrafica(RagioneSociale)
- Sito
- Tel
- Email

## Disponibilità
- ID auto_increment PK
- RagSoc --> FK in Anagrafica(RagioneSociale) 
- Inzio
- Fine 
- PostDisp

## Assegnazione 
- ID auto_increment PK
- RagSoc --> FK in Anagrafica(RagioneSociale)
- NomeAlunno
- CognomeAlunno
- ClasseAlunno
- IDdisp --> FK in Disponibilità(ID)
