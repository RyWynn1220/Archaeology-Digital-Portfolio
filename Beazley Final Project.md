# Topic Modelling Greek Vases #
### Stephen Pittman, Ryan Wynn, Paul Topazio ###

**Brief Explanation of Project**
In this project we analyzed a data set of ancient Greek pottery from the archives of the work of Victorian scholar John Beazley using a method called Topic Modelling.
Topic Modelling is a type of classification system using computer learning to separate a corpus of texts into topics of a specified number, k.

After much deliberation and experimentation with different numbers of topics, we found that 11 topics (k=11) produced the clearest ones. Each topic is represented by 15 heighest weighted terms that define the topic. In our tables below, each term's numerical weight coefficent is written next to it.

**Topics:**

| Topic 0 -       | Topic 1 -       | Topic 2 -      | Topic 3 -      |
| -------------   | -------------   | -------------  | -------------  |
|seated 0.06154684278178771|fish 0.02159156339409686|hare 0.03415465494916104|palmette 0.06015944389632018|
|woman 0.04240026327517918|wedding 0.009702233866085933|birds 0.025027107242055924|floral 0.053082176483998385|
|dionysos 0.036613738396286295|cave 0.00922848536684775|carrying 0.02498444842127887|dionysos 0.04109027131388299|
|maenad 0.030223065443465254|agriculture 0.009028784868310682|dogs 0.016845245294631685|drinking 0.03861595112360884|
|women 0.029669530855946792|picking 0.008357331750227254|named 0.015058342394513497|horn 0.03701588139998729|
|satyr 0.028731931635003916|splanchnopt 0.0075099423284451326|hunt 0.014510623897788524|chain 0.03609863483758876|
|chariot 0.024809103740859352|tendrils 0.006803826996137123|ilioupersis 0.013779048754843237|vine 0.035424908868996616|
|thyrsos 0.023875347342898288|hetaira 0.0058020206503172495|chasing 0.01283383234786193|lotus 0.0352701615467623|
|maenads 0.02093098751389732|clothes 0.005649561735314312|boar 0.012148428623998354|lion 0.02962655437285052|
|satyrs 0.018369581987961594|shells 0.0054382801977317635|priam 0.011878327092953039|animal 0.02913792394114074|
|eros 0.01626402040333153|women 0.005029789114815541|maenad 0.011642456228045718|herakles 0.028905380436172193|
|hermes 0.016089848381495256|ephedrismos 0.005013942341830425|aineias 0.011585252103116348|eyes 0.02845600058176527|
|dancing 0.015412471977696471|vessel 0.004445052885521618|women 0.010798148554031379|satyr 0.02706065925990217|
|domestic 0.015217608818611297|basin 0.004262247916020285|anchises 0.010703970757369664|frieze 0.026290386173681856|
|stool 0.014892484905352707|artisans 0.0042095429253507614|boreas 0.009886339869660869|satyrs 0.02484832364549125|

| Topic 4 -      | Topic 5 -      | Topic 6 -      | Topic 7 -    |
| -------------  | -------------  | -------------  | -------------|
|athena 0.1535221016785924|draped 0.11488903604339727|man 0.055493960790379035|orpheus 0.019230770393598183|
|satyr 0.0586649825102914|youth 0.07160560696464788|warrior 0.04957797779655338|death 0.018475660836068362|
|gigantomachy 0.031900221582053176|woman 0.05990125636195818|woman 0.03826434679191726|thracian 0.018032846951865415|
|gorgoneion 0.024730812986973213|youths 0.053332215091238186|warriors 0.037248236745505044|tray 0.017598796070459097|
|achilles 0.02252495280545879|man 0.04256769898564126|shield 0.03378820974565456|graffito 0.012587746816491984|
|device 0.02198143056351871|figure 0.02916928014020629|youth 0.029483776958354694|pig 0.010471245715115096|
|chariot 0.018781448134194086|staff 0.02848823259814187|chariot 0.02793256390980425|sword 0.0067840825182497394|
|giant 0.01739040405673182|men 0.022469798164968604|device 0.025387909904513645|spit 0.006520483267776433|
|ajax 0.015471824478298995|seated 0.018081107784877936|fight 0.0237018613616717|maenad 0.00617930905184246|
|shield 0.01295823794799921|suspended 0.016981624295938122|draped 0.02347099556743232|masks 0.005446571479339898|
|herakles 0.011187866803356573|women 0.016217902216528197|departing 0.0209814034854488|theatrical 0.005185556632102864|
|frontal 0.010733909129912466|komos 0.01575035977884761|spears 0.018677529525576622|tattooed 0.005136631389859689|
|zeus 0.010592038700883386|running 0.015257316712143228|spear 0.016636442641413857|lines 0.005002212425707252|
|giants 0.010014813895034927|symposium 0.014759191492966475|chlamys 0.015082109965401349|phalloi 0.0049749043379305035|
|poseidon 0.009773489125176853|head 0.012458735173554116|sceptre 0.012823377918563677|circe 0.004735924154069464|

| Topic 8 -   | Topic 9 -   | Topic 10 -      |
| -------------  |-------------  | -------------  |
|floral 0.09734601778050864|bull 0.06642668470669032|demeter 0.03177749091193323|
|palmettes 0.08169999302855566|herakles 0.04316164751133965|persephone 0.02815801411406043|
|ivy 0.06883462905067654|suspended 0.035009667404310094|sceptre 0.026713436550614172|
|pattern 0.044954750022085904|theseus 0.03381270871219632|triptolemos 0.02532509490973158|
|wreath 0.03616134656942815|quiver 0.02770388730305399|winged 0.021334539170559903|
|siren 0.03347981401242452|cloth 0.02645510182075075|named 0.01916374635539527|
|swan 0.03263744563496845|child 0.026069548701160836|perseus 0.016696445497904843|
|bird 0.02529132247694998|ram 0.022188587766062605|corn 0.01542751606222921|
|sphinx 0.021075997654648727|club 0.018999204129304705|tendril 0.013909627031787023|
|owl 0.019161615161180708|columns 0.016623436218368468|torches 0.011966431770255805|
|swans 0.018900260883830938|minotaur 0.015671336429131138|hephaistos 0.011603432075583564|
|olive 0.01770413656563269|bow 0.015452751692972402|torch 0.010057676242610473|
|berries 0.01428025695097647|fig 0.01446814989710112|chariot 0.009486522932165864|
|leaf 0.011965329144628709|lion 0.01305192983619138|medusa 0.009343679194712023|
|laurel 0.011875359049555279|chous 0.01262298760595872|woman 0.008914914441133927|

**Topic Descriptions:**

0. Dionysian revelry

1. Household affairs, particularly of women

2. Hunting and Trojan War

3. Natural Dionysian

4. Mythological Monsters, Heroes and Deities

5. Social/drinking

6. Warrior

7. [Unclear]

8. Flora and fauna

9. Heroic

10. Mythological, particularly of Perseus' myth and agricultural deities

**Links:**

Link to Delimited Text File: http://shot.holycross.edu/ada-vases.tsv

Link to our work on a Jupyter Notebook: https://notebooks.gesis.org/binder/jupyter/user/rywynn1220-arch-gital-portfolio-jnikklw4/notebooks/Beazley_Topic_Modeling_Final_Project.ipynb