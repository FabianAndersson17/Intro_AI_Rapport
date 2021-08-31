# Förut se huspriser

För att kunna förut se huspriser behöver man data på huspriser och hur det har utveckalts över tid. Denna datan kan man få från fatighetshemsidor genom data på hur mycket ett hus såldes för, antal rum och plats som huset ligger på. Denna datan måste tas från flera olika fastihetshemsidor och över en väldigt lång tid för att kunna få en bra data mängd. Datan får för varas på servrar upp sorterat efter datum och var datan kommer ifrån. Denna datan måste man även sammala in från massa olika år tal för att kunna se utvecklingen över tid och genom det förut se hur huspriserna kommer att ändras i framtiden.

Denna datan kan man ha det i en graf med en axel för tid och en axel för pris, där x-axeln är tid och y-axeln är pris. X-axeln måste markeras med år för att lättare kunna se vid vilket år det är man kollar och y-axeln markeras med medelpriset för bostäder med passande mellanrum mellan de olika priserna. Gör man på detta sättet får man en graf där man kan kolla av hur mycket medelpriset för bostäder förändrats över åren och se förändringar i priser för att kunna se tidigare förändringar och förut se förändringar i framtiden. Sedan får man ta in en fel faktor för olika ekonomiska problem och katastrofer.

För att bearbeta datan till rätt format behöver man rensa bort all data som inte har med medelpriset för bostäder över tid att gör. Ut ifrån den rensade datan kan man ta fram specifika datum och sedan se priser för bostäder de årtal eller ta fram ett specifik pris och kolla vilket årtal priserna låg precis där. Man kan även ta fram vilka år huspriserna skönk och vilka år det steg. Samt kolla koressponderande priser och datum med om det var ekonomiska problem vid de tidpunkterna.

Linjär regression är när data sätt ut som punkter i ett rutnät med position varierande på vilken data som pricken representerar. I detta fallet är prickens position basserad på medelhuspriset vid en viss tidpunkt där y-axeln vissar hur mycket medel priset för en bostad var och x-axeln vissar vilket år det är. Med linjär regression sätts det ut en prick vid ett år och med koresponerande medelpris för bostad. Sedan när fler punkter sätts ut kan man dra ett sträck igenom punkterna som vissar hur datan har förändrats. Om mängden datapunkter öker kommer även noggrannheten på den linjära regressionen öka. Dock kan den linjära regressionen vara felaktig om datan som man sätter in har stort varierande värde det kan ge en felaktig bild.

//Driftsätta modellen

## Källor:
- https://dqydj.com/historical-home-prices/#How_do_I_cite_this_data
- https://www.redfin.com/city/11203/CA/Los-Angeles/housing-market#demand
- https://en.wikipedia.org/wiki/Linear_regression
- https://www.talend.com/resources/what-is-data-processing/