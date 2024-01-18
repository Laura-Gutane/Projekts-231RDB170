# Projekts
*Projekta uzdevuma detalizēts apraksts:*

**Projekta mērķis.**

Projekta mērķis ir izveidot programmu Python, kura analizē ģimenes ikmēneša budžetu, izmantojot datus no excel faila. Šī programma ir paredzēta lai izsekotu ģimenes plānotos izdevumus kopā ar faktiskiem izdevumiem un aprēķināt starpību starp izdevumiem. Kā arī programma veic atbilstošus aprēķinus: saskaita kopā visus patēriņus, plānoto budžeta naudu un starpību. Svarīgi arī ir tas ka programmai ir jāizvada un jāsaglbā visi iegūtie dati. Programma izvada atbilstošo summu zem katras kategorijas. Tātad cik kopā bija liels budžets, cik naudas rezultātā bija patērēts un pāri palikums. Papildus tā izvada starpību starp datiem noteiktajā stabiņā. 


**Izmantotās bibliotēkas.**

Openpyxl

Projekta ietvaros izmantoju bibliotēku Openpyxl, kura ir viena no izplatītākām bibliotēkām kura nodrošina iespēju strādāt ar excel tipa datiem. Izmantoju šo bibliotēku lai darbotos ar excel failu. Lai sasniegtu projekta mērķi, izmantoju vairākas funkcijas no bibliotēkas Openpyxl. Kuras ļauj veikt dažādas operācijas ar datiem no excel.Izlasīt/ievadīt datus excel formātā utt. Openpyxl ir piemērota strādāšanai ar excel failem un piedāvā daudz dažādu funkciju, tāpēc izvēlejos šo bibliotēku.


**Programmatūras izmantošanas metodes.**

Python programma darbojas vairākos posmos, kurus var kopā iedalīt 3 galvenajos: Datu nolasīšana no excel faila, datu aprēķini un visbeidzot ieguto datu saglabāšana jaunā excel failā. 

Datu lasīšana
    Nolasa datus no excel faila izmantojot "load_workbook"
    Nolasa datus to excel tabulas

Datu aprēķini
    Aprēķina datu starpību un ieraksta rezultātu
    Aprēķina dato kopēj summu vienā kolonnā un ieraksta rezultātu

Datu saglabāšāna
    Saglabā datus jaunā excel failā   


**Kā izmantot programmu?**

Lai izmantotu doto programmu, lietotājam ir nepieciešams ievietot mapē valadzīgo excel failu ar mēneša budžeta datiem.(Ievietot vienā mapē kopā ar programmu).
Tad ir nepieciešams palaist Python programmu. Tā veiks visus nepieciešamos aprēķinus un izveidos jaunu excel datni ar jau gataviem saglabātiem aprēķinu rezultātiem.
Apskatiet jauno failu ar visiem izdevumu aprēķiniem kopsummas un starpības. Jauns excel fails tiks saglabāts tajā pašā mapē, kur bija ievietots sākotnējais fails.

*Lai nodemonstrētu programmas darbību un rezultātu, tika izveidots video. Video var apskatīt šeit:*
https://youtu.be/6YdehiPtfvQ?si=q4oUvUJnnZ0wGLz1

*Secinājumi*

Programma ir noderīga ģimenei, kurai katru mēnesi ir nepieciešams analizēt savu budžetu lai spētu veikt uzlabojumus nākamā mēneša budžeta plānošanai. Datu aprēķinu automatizēšana spēs ģimenei ietaupīt spēku un laiku, un noteikti atvieglos budžeta pārvaldīšānu. Programmu var arī izmantot citi lietotāji, kuriem būs noderīga šī veida budžeta programma.