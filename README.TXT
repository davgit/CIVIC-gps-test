This web site was built for Google Geek Street Festival, occuring on
July 22, 2015, by Tom Kompare of the University of Chicago as a
demonstration of how AGPS works in mobile devices and intercations
with web sites.

This code can be placed on any web server that supports serving
static web content. There is no back-end/server-side processing.

This code falls under licenses found in LICENSE.TXT.

Some javascript code was derived from Chris Veness's work found at
https://github.com/chrisveness/geodesy. Thanks Chris! It would have
taken much longer to do this without your blood, sweat, and tears.

Some other javascript code were from Derick Bailey's work found at
http://derickbailey.com/2014/09/21/calculating-standard-deviation-with-array-map-and-array-reduce-in-javascript/
Thanks, Derick! You rock.

Working site: http://uchicago-tkompare-gps-test.appspot.com/


zzzzzzz#zzzz##zzzzzzzzzzzz#zzzzzznnnMWMMWMnzzzz##z#z###zz##z####zzz################zzznMMMMMMMWWWWxnnxMW@@@Wxnnnnznnnnzzz
zzzzzzz#zz##zzz#zzzzzzzzzzzzzzzzzzzzxxnnnnzz####z#####zz##zz####zzzz#################znMWMMMMMWWMxxxM@@@@@@@Wnnnnnnnnnnnz
zz#z#zzzz####zzzzzzzzzzzzzzzzzzzz##zzzzzzzzzz##zz####z#zzz###zz#zzzzz###z###########zznMMMMMMWMMxxxW@@@@@@@@@Mnznnnnznnnn
zzzzzzz#z#zz#znxnzzzzzzzzzzz#zzzzzz#zzzzzzzzzzzzzz#zzz#z#zzzzzzzzzzzz####z#######zzzzzxMMMMMMWMMxMW@@@@@@@@@@Wnzzzzzznnnn
zzzzzzzzzzzzzzxMMnzzzzzz#zz#z#zzzzz#zzzz#zzzzzzz#zzzzzzzzzzzzz##zzzzzzz####zzzzzzzzzzzMMMMMMMMMMM@@@@WWW@@@@@@xzzzzzzznzz
zzzzz#zzzzzzzzx@WWxzzzz#zzz#zzzzzzz#zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznMMMMMMMMMW@@@WWWWWW@@@@@Mzzzzzzzzzn
zzzzzzzzzzzzzznW@WWMnzzzzzzzzzzzzzzzz#zzz#zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzxMMMMMMMMM@@WWWWWWWWW@@@@Wzzzzzzzzzn
zzzzzzzzzzzzzzzM@WWWWxzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznMMMMMMMMM@@WWWWWWWWWWW@@@Wnzzzzzzzzz
zzzzzzzz##zzz#zn@WWMWWxzzzz#zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzxMMMMMMMM@@WWWWWWWWWWWW@@@@nzzzzzzzzz
zzzzzz#z#z#####zM@WMMWWMnzz#z##zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznMMMMMMMM@@WWWWWMMWWWWWWW@@@nzzzzzzzzz
zzzzz#z##z#####znWWWMMWWWxzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznzzzzzzzzzzzzzzxMMMMMMMW@WWWWWMMMMWWMMMW@@@nzzzzzzzzz
zzz#z#z##zz##z#zzx@WMMMWWWMnzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznzzzzzzzzzzzzzzMMMMMMMW@WWWWWWWMMMWMMMMWW@@nzzzzzzznn
zzzzzz#zzzz#####zzMWWMMMWW@WxzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzxMMMMMMW@WWWWWMMMWMMMMMMMWW@@nnznnnnnzz
#zz#zz#zzzz#z###zznWWMxMWWW@WMnzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznMMMMMMW@WWWMMWMMMMMMMMMMMWW@Wnnnznnznzz
#zzzzz##zz####z##zzxWMxxMMWW@@WxnzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznxMMMMMW@@WMWWMMMMxMMMMMMxMMW@Wnnnnnzzzzz
zzzzzz##zzz##zzz#zzzxMxxMMMWW@@WWxnnzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznxMMMMMW@@WWMMMMxMMxMMMMMMMMWW@Mnnzzzzzzzn
zz#zzz#zzz#z#####zzznMxxMMMMWW@@@WMxnzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznxxMMMMW@@WWMMMMMxnxxMMMMMMMMMW@Mnzzznzznzz
zzz#zzz#zzz#z#z##zzzzxMxxMMMMWW@@WWWMnnzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzznxxMxMMW@@WWWMxMMMMxnnMWWMxMMMMW@Mnzzznnnznz
zz#zzzzzz##z#####zzzznMMxxxxxMWW@@WW@WMxzzzzzzzzzzzzz##z#z#zzzzz##z#zzzzzzzznxxxxMMM@@WWWWMMxMxxxnnxMWMMMMMMW@xnnzzznzznn
zzzz#z#zzzzzzzzz#zzzznMxxnxxMMxMW@@WW@@WMnzzzzzzzzz#####+#+########+######zznxxxMxMW@@WWWMMMMxMxxxnzMWMMMWMWW@xnnznznznnz
#zz#zzzzzzzzzzzzzzzzzznxnnxxxMxxMW@@@W@@WMMnzzzzzz##*+++;i;*+#++++*ii*+*ii+znxxxxMW@@WWWWMMxxxxxxMxzxWWWWMWWW@xnznnzzznnz
zzzzzzzzzzzzzzz#zzzzzzznnxxxxnnnxMWW@W@@@WWMnzz#z#+*;i*i..,:;ii;;;;,,::;;;i+znnxM@@@@WWWMMxnxxxxxnxnnWWWWWWW@@nnnnnnnznnz
zzzzzzzzzz###z###z#zzz#xzzzznnnnnnMWWWWW@WWWMnz##+;:,,;,``..,::.,.,.,,,:;;;i*+zxW@@@WWWMxnxMMxnxxnnnzMWWWWWW@Wnnnnnnzznnn
zzzzzzz#############z##nzzz##zznnnnMMWWWWWMWxnz+*i,...,.`.`..,,`....,,,:;**++*zW@@@WWWWMxnnzznnnxMnxzMWWWWWW@Mnznnnnnnnnn
zz#z####################zzn#+#zzzzznxxMWMWxxn#+*i:....,.`..`.,.`....,,::;*+nnxW@@@@WWWWMxnzznznnnxxxnMWWWWWW@Mnnnnnnnnnzn
zz#################z###+znz#z#+#zzzzzznMMMn#++i;;,,,,,,...``.,.`..,,,,::;**nnxn@@WWWWWMxnnxnnnzzznnxxM@WWWWW@xnnnnnnnnnnn
zz######################zz##z##++####zznz#z*;*::,,,,,,:,.``.,,,`.,,,,,;:;i*###zMMMWWWWxMMMMMxxnnznnnMWWWWWWWWnnnnnnnnnnnn
zz#######################z###+++++#z#z##+i*ii;:,..,,,::,.``.,,,`.,::,.:::i;*+*#zzxMMxxWWMMMMMMxxnzxnMWWWWWWWWnnnnnnnnnnnn
z##########################++##zzz+#+#+*+i;;;,:...,,:;:,``..,.,..,:;:,,::;:i***##xz#nWMWWWWWWMMMxnxMMWWMWWWWxnnnnnnnnnnnn
zz#######################++##zz#zzz++*i;i*,::,,.,,,:;;;,``..,`,,.,;i;::::;:iii*++++zxxMMWWWWWWWWMMMWWWWWWWWWnnnnnnnnnnnnn
zzzz####################+*+zzz#####+*;;;:;,,,,,,.,,:;i;.`.`,,`::.,;i;::::;:;;;**+i+zznzxMMMMMMMMMMMWWWWWWWWMnnnnnnnnnnnnn
zzz##########z##########**znznnz#***;:,,:,,,,.,,.,,:;i;..,.,,.:;,:;ii;;::;:;;;;iii+#++znxxxMMMMMMMWMWWWWWWWxnnnnnnnnnnnnn
zzz#####################++znnnnz+i::,.,..,,,,.,,,,::;i:,,,,;::;;:;i*i;;:::::;;;;;i+***++znxMWWMWWMMWWW@WWWWnnnnnnnnnnnnnn
zzz###################zz#znxnnz**;,.,....,,,,,,,,,:;ii;,,::;;;;:;;i+*i;;;;;:;;;;;iiii**+zxxMMWWWWWMMWWWWWWMnnnnnnnnnnnnnn
zz###################zz#znnxn##*;:,...`..,,,:,,:::;;ii;.::;iiii:ii***;i;;;;;;;;;;iiiiii*+zznxMMWWWWWWWMWWWxnnnnnnnnnznnnn
zz################zzzzzzznxxn#i;,,.......,,,:,::;:iii*;,::;iiii;i+++*iiiiii;;i;i;;;;iiii++#nxxMW@WWWWMWMWWxnnnnnnnnnnnnnn
zz###########zzzzzzz#z##zxxMxz+:,.`.....,,:;;:;;;;*ii*;:;:i+ii***#++*i*iiiiiiiii;;;;iii*++#znnxMW@@WWMWMWMnzznnnnnnnznnnn
zzz######zzzzz##zzz#####zMMWMn#;,....,,,:::ii;;*i****+ii;;i+**++*###+*****i***iii;;i;;ii**+*++zMW@@W@WWWWMnzznnnnnnnnnnnn
zzzzz#zzzzzz#############xMMMn*;...,,,::;;;iiii++****++iiii++*##+####++*+**+***iiiii;;ii*ii**+zxW@@W@@WWWMnzzznnnnnnznnnz
zzzzzzzzzz###############zMxMn*:,.,:,::;;ii;*+*#++***##*i*i*+#zz##zzz##++++++***i;;;;;;iiii**+zx@@@@@@WW@Mnzzzznnnnznnnzn
zzzzz#z##################zMWxx+:,,::;;;ii**i+#+z++*+#nn*iii*+zzn###znzz#+##++*iiii;;;;;;;ii**+nW@@@@@@W@Wxzzzzznnnnnnnznn
zzzz######################nWxzi:::;;i*ii***++zzn+++#znn*ii**#zxnzzznnnzz###+****iiiii;;;iiii*#xxW@@@@@@@Mnzzzzzznnnnnnnnn
zzz########################zn+;;;iiii**+*+*#znxn++#zznn*;i*+znxzzzznxxnzz##++++**iiiiiiiiiii*+#xW@@@W@@@Mnzzzzzzznnnnnnnn
zzz##########################*iii*****+##++#nxxx###znxzi;i*#nxxnzzzxMxnzz#+zz#+****iii;iiii**++zWWW@@@@Wnzzzzzzzzznnnnz#+
zzz##########+##############+ii*+++*+++###znxMxn#zzznn#ii*;#xnxxnnznMMxnz#nnzz++****iiiiii***+#xMW@@@#@xzzzzzzzzz+++#*+##
zzz###########+############+***++++++*++##nMMMMxzzzznx+i+*:+xxnnnnnxMMMxnnnnnz#+*++*iiiiii***+#xWW@@##@nzzzzzzzz#i+++#z##
zzzz##########+############**++###+++++##znWWWMxzznnxnii#+:*nxxnnnxxMWWMxnxxnz##++***********+#xW@@@##@xzzzzzz##++#####++
##z###########+###zzzzzz#+***+zzz########znMWWMxznzxx+;*##;;zxnnnnMMWW@Wxnxnnzzz####+++******++zMW@@##@z#######z+++++#zz+
##z###########+##zz###+++**i*+#znz#####zzzxxWWMxxxnxni;+##i:*xnnxxMW@@@Wnxxnnnnzz######++++***+#nxW@@@@+#n##xnnz++#z#zzz+
#zzz######z##+++##z##++**ii*+#znzznnz#nMxnxMMxxxxxxx#;i##+;,;xMxxMWW@@@WMxnxxnzzzznzzzzz#+*****+#nMW@@@nzxxzznn######zMMn
zzzz#######+++#+#z###+*ii;*+zxxxzznziiz@@MxxxMxxxxxni:i***:,;nWxMW@@@@WWWMMxxnzzzzznnnnnz#+++***+#nMW@@Mzxn#znxn#++##xMMx
##zz######++++#######*i;;;i#nMMx#zxz**M@@@M+zxxxxnzz::iii:,,izWWWWW@@@@WWWMMxMnnznnnnxxxz#++++***+#nMW@Wnnn#zxMn+zznnMMWM
##zz####+*++++##+#zz+i;;:;*#xxxx#nx#:+W@@@Mi,#xMMxnz:,;i:,.:ixMWW@@@@@@W@@@@WxMxxxxxMMMMxz##++****+#nMWWxxxz+xMnzxz+nnznn
###z###+***+++#####+i;;::;+nxnnn#nMn+zW@@@xi.+nMMMxz:,::,..:*M@WW@@@@@@WW@@@@@Mx#zWWxMWWWMxz#++****+#nMWxxxz#xxxnz+*+##nx
##zzz#+***++++#zz++i;;:::;+znnnn#nMnxM@@@@z;.#zxMMMz:.....:;+M@@@@@@@@MMW@@@@@Wn#+xWxxWW@WMnz#++***++#znnnxnzzxz*++#znxxM
###z#+***+++++###+;;;::::;*#zznzznWMxxW@@M*,:n#xMMxz;```,,;*zW@@@@@@WWxxW@@@@@@xz#xMxMMMWWWMnz#+****++#z#zx#ii+++#znnxMMM
####+***+++#++###i:::::::;*+#zzzznMWxnxWWz;,+x#MMWx+;```,:i+nW@@@@@WWMnxW@@@@@@xnnMMxMMMMMMMxz#++***++++++#+++#zxxxMxMxxx
###+**i*+++#+###*;;:::::,:i+znnnznxMWMxxxn#+xnnMxMz;,` `.:;#nM@@@@WWMMznM@@@@@WMxxWxxMMMxMMMxnz#+++***++**++znxxxxxMMMMMM
###**ii++++++##+i;::::::::i+znnnnnnxMWMxxxnnn#nMnni,````.,;+nxW@@@WMMx#zx@@@@@WMxMMxMMMMMMxxxnz#++++++++***#nxxMMMWMMMMMx
##+*i;i*****+#+i;:::::;:::i+znxxnnnnnxxxnzznx#zMn+;.````.:;*znW@@WWMMMz#zxW@@@MxMMMMMMxxxxxxnnz#+++**+***#znMMMWMMWMMMMMM
##*ii;*++++znx+;:::::;;;::i+znxxxxnnzzzzznnxxxnMz*:....,:::i+nM@@@WMMMMz#znMMxxMWMMMMxxxxxxxnzzz#++*****+#nxMMMMWMWMWMMMM
+ii*+++#++znxzi:::::;;;;::i+znxxxxnnzzzznxnxMMMn+:,...,:::::*#M@@@@MWMMMxxnxxMWWMMMMMMMxxxxnzzz##++*****+zxMMWMMWMMMMMMMM
ii++##z##+znz*;:::::;;;:::;i+znxxxxxnzznnnnxMMMzi`..`.,::,,:;inW@@@W@WMMxxMMMMMMMMMMMMxMMxxnz#####++**ii*+nMMWMWWMMMMMMMM
+**+*+*++#zn+;::::::;i;:,,:i+znxxxxxxnnxnnxxxMx+,`....,::::::;#x@@@@@WWMMMMWWMWMWMWWWWMMxxxnz###++++**ii*#nMWWWWMWWWMMxWM
+******+#nn#;:::::;;;i;:,::i*#znnxxxnnnnxxxxxnz;``.,,,:::::::i+nW@@@WWWMWMMMWMWWWWWWMWWMxxnzz#++++++**ii*+zMWWWWMWMMMMMMM
+*+**+++#n+i;::::;;;;;;:,:;;*++znnnnnnnnnnnnnz;.``.,:::::::::;*#M@@@MWMMMMWMWWMWWWWWWMMxxnzzz#++*++***iii*zxWWWWWMMMWMMMM
#+++**++##;:::::;;;;ii;:,::;*+++#zznzzzz##z##*,```..,:::;:::;;;*zxWWMMMMMMMMWMMWWWWWMMxxnnznz#++******iii+zxMMWWMMWMWWMMM
+++++++##;:::::;;;iiii;:,,::i*+####zz######++:.```.,:::;;;::;;:;#nxMMMMMMMMMMMMMMMMMxxxxxxnzz#+******ii;i*#nMWWWWWMMMMMMM
#++++##+i:::::;;;iiiii;:,,::ii*+#z#++#+++*i;:`.,`.,:;i;;ii;:;;::i#nxxxxMMMxxMMMMMMMMMxxnnnzz#++****iii;;i*#nMMMWMWWMMWWMM
#######*:::::::;iii**i;,,,::;i*++++++**+*;:.``.:.:;;i*;i**i;*#;,,i#nxxnxxMxxxxxxxxxxxxnnzzz##++****iii;;;*#nMWWWWMWMWMWMM
++****i;:::::::;;iii*i;:,,:::;i**+*****i;:..```.,izi;*;*nz+*+*;,,,i#nxxnnxxxxMxxxxxxxnnzzz##++****iii;;;;*#xMWWMMMMMMMMMM
iii*+i;::::::::;;iii*i;:,,,::;;;iii**i;:,.``````.,i#;*i#n#ii;::,,,:;*#nxxnznnnnn##znnnnzz###++***iii;;;;;+zxMMMWMWMMMMMMM
*++#*;:::::::::;;iiiii;:,,,,::::;;;;i;;,.```````.,:+#z**i::,::,,,,::;##nxxnnnxxnnnz##znzz##++***iiii;;:::i#zxMMMMMMWMWWMM
##+*;:::::,:::;;;i****;:,....,:;;;;;;;:.````````..,i+z*i::,,,,,,,,,,:;*#xMMxnnnzznnnnnzz##+++****ii;;;::::i+#nxMMMMMWWMWM
##*;::::::::;;;;ii****;:,.....,::;;;;;,``````....,:;*#i;::,,,,::::::,::i+znxxnnnzzzzzzz###+++****i;;;::,,:i#nxxMMMMMWMMMM
+*;::::,:,::;;;ii***+*i;,......,,:;;;:.`````.`...:;i+z*i;:;:::::::;:::::i+#znnzzzz###++#+++++**iii;;::,,,:i+zxMMMMWMWMMWM
*i::::,,,:::;;iii***+*i;,......,:::::,.````....,:;*+#z#*i:;;;i;::::;::;;i+#zzz####z#+++++#++++*ii;;:::,,,:;+znxMWMWWWMWWW
i;:::::,,,:;;iii**++++*;,......,,::::,.```...,,;ii;ii*+##*ii;ii;i;:::,::;i**++++*++###+++++++*ii;;:::,,,,,;*zxMWMMMWWMMMW
;:::::,,,::;ii***+###+*;,.````..,,:::,.```.,,,;;,.:::ii*+##+iii;;i;::::::i*******+++****+++**ii;;:::,,,,,,;*#nMMMWMWWWWMW
::::::,.,;;;i**+++#+++*;,.`````..,:::,,.`...,::...::;;iii*+##+*iii;;:;;;;*++#+*i*+****+**i**ii;;:::,,,..,,;i#zxMMMWWWWWWW
::::::,,::ii**+++++##+*;,.``````..,::,,...,,::,....,;;iiii*+#z+***i;;:;;;*****+***++#+****i;;;;:::,,.....,:i+xMMMMWWMWWWM
,,:::,::;;i*++++###z#+*i,.```  ``.,::,,...,,;,,,```.,;:i;iii+#z+***ii;:;;i*+**i*##+++++*ii;;;::::,,,.....,,:*#nxMMWWWWWWW
,,:::,:;;i***++#######*i:.````  ``.,::,.````......``,;::;iii**+#+*iiiiiii*+**+***++++**ii;;;:::,,,......,,,:i+zxMMMWMMWMM
,:;;::;;;i***+#####z#+*i:.```   ``.,,:,..`````....``.:;;;;*iii*+++i;;;;ii*****++*****iii;;;:::,,,.......,,,:i+znxxMWWWWMM
,;;;i;;i;i**+#####z#++*;:.``    ``..,,,,...`````````.,:;;;iiiii**+*i;;:ii;ii*+**+*iii;;i;;::::,........,,,,:;*#nMWWWWWWWW
,;iiii;iii*+++##zz####+i:.``    ```..,,,,,,.````````.,:::;;iiiiii**i;;;;i;ii*++*ii*i:;:;;;::,,,,.....,,,,,::i+znMWMWWWMWM
,i***iii**++#+#zzzzzz+*;:,``      ``..,,::::,,,.````.,:::::;;;iiiii;:;;:ii;iii**ii;i;::::::,,,,,........,,::i#nxxWWWW@WWM
:i*+**i*+#+++###znzz#*ii:,.`      ```.,,:::::::,.`````..,,::::;;;;;::;;;;ii:iiiiii;:;;::,,,,,,,.,,,,,,,.,,::;*+nxMWMMMWWW
;*+++++++##+###znnnz++*i:,.``        `.,,,:::::::,``````..,,,,:::::::;;;:;ii;i;;;;;;::::,,,,,,,,,.......,,::;i#znMW@WWWMM
i*+++##+++####znnnz##+*;:,.``       ```..,::::;::,..`````.....,:,::;;;;;:;;i;:;;;;;;::,,,,,,,,,,,,.,...,,,::;i*zxWMWWMMWM
*+++#zz##++#znnnnz##z+*i:,.```      ``...,,:::;;:::,,,```````..,,,::;;;;;:;;;:;;;:::::,,,,,,,,..,,,.....,,::;;*nxWWWWMMWW
#++##zzz#++#nnnnz##zz#*;:,..```     ```..,,,::::::::::...`.``..,,,,,:::::,:::;::::::,,,,,,,............,,,:::i#xWWWWWWMWM
z+##zzzn###znnnn#zz#+*i;:,..````    ``..,,,,,:,:::::::,,,.,...`.,.,,,,,:,,:,,::,::,,,,,,,,,,.........,,,,,:::i+zxMWWWWMMM
#zzzzznz#nnnnnnz#zz#+*i;:,...````  ````....,,,:::::::,:,:,,,,..,.`.,,,,,,,,,,,,,,,:,,,...,,,.......,,,,,,:::;i+#nxWWWWWMM
#znnzzz#znxxnnz#zz##+*;:,,...```````````...,,,,,::::::::::,,,..,.`..,,:,.,,.,,,,,,,.,,,...,.....,.,,,,,,,,:::;i+nxMWMWMMM
#znnnz#znnxxnnzznzzz+i::,,....````````````...,,,::,,,,:::::,,.,,.`...,,,.,........,,.,....,,,,,....,.,,,,,::;;*#xMMWWWWWW
zzznz##znnnxxnznnzz#+i::,,.....`````````````..,,,,,,,,,:::::,,,..`...,,.,...,,,,,,,,,,,,,,.,,,,.....,,,,,::::;i#xMWWWWWMW
zzzzzz#nnnnnxznxnzz#*;::,,...````````````````....,...,,,,:::,,......,.,,,,.,;;;;;;::;::,,,,,,.......,,,,,::::;i+nMMWWWWWM
zz#znnznnxnnnnxxnzz#*i::,,...``````````........,,,...,,,::::,,...,::,,::;;;iiii;;;;:;;::,,,,.........,,,,::::;i*#xMWWWWWW
zz#znnnnnnxxznxxnn#+*;;::,,....```````......,,,:::,.`..,,::,,,,,;;;;:;;;ii;ii**ii;;:;;::::,,..........,,::::;;;i+nxMWWWWM
z#zzzzxnnnxxzxxnz##+ii;::,,,......````....,,,,,::::,.....,,,,::;;;i;;iiiiiii**ii;;;;:;::::::,,,,...,,,,:::::;;;i*#xMWWWWM
zzzzzznxnnnnnxxxnz#+*i;::,,,......````....,,,,,::::::,,....,::;ii;iiiiiiiiii***i;;;;:;::,,,,,,,,,,,,::::::::;;;i+#xMMWWWW
zzzzzznnnnnzxxxxnz#+*i;::,,.......```....,,,,,,::::::,,.`.,::;;i;;iiiiiiiiii***i;;;;::;::,,```......,,:::::;;;;i+zxWMWWWW
zzzzzzznnnnzxMxnzz#+*i;::,,.....`.........,,,,,,:::;:,..`,:::;::;;;iiiiiiiiii*i;;::::::::,,,.````...,,,:::::;;;i+nxMMMWWW
zzzzzzznxxnzxxxnz##*ii;::,......``.....,,,,..,,:;;:::,..,,,,:::::;;iiiiiiiiii*i;;:::::::::,,,....`....,,:::::;;*#nMW@WWWM
zzzzzznnxxxzxxxnzz#+*i;:,......```....,,,,,,,::;:::,:,,,,,,,,:;;::;iiiii*i****i;;::,:::::,,,,,,,......,,,::;;;;i#xWMWWWWM
zzzzznnnxxxnxxnzzz#+ii;:,,.....```.....,,,,::::::,,,:,::::::::i;::;iiiiiii***iii;:,,,,,,,,:,,,,,,,,,,,,,,::::;;;*zMMWWWWW
zzzznnnnxxxnxxxnz##+ii;:,,......```....,,,,:::::,,:::,::,::::ii:.:;iiii*iii****i;:,,,,,.,,:,,,,,::::,,,,:::;;;;;;*nMWWWWW
zzzznnnxxxxxxxxnnz#+i;;:,,......`.......,,,:::::,::,:,,:,:;;ii;,.:iiiiii**ii***i;:,,.,,.,,,,,,,::::::::::::;:;:;ii+zxMMWW
zzznnnxxxxMxMxxnnz#+*ii;:,...........`....,,:::::::,,,,,,:;;*;:..:iiiiiii*i*****;:,,,...,,,..,,::::::::::::;;;;;i+#nxMWWW
zznnnxnxxxMxMMxnnz#++*i;:,.......,,..`.`...,:::::::,,,,,,;ii;:.`.;iiiiiiiiii****i:,,,.......,,,::::::::::::;;;;;;*zxMWMWW
nnnnnnnxxxMxMMxnzz##+*;;:,,.....,,,........,,,::::,,:,,:,;;;;.``,;iiiiiiiiiii***i:,,,.......,,,,,::::::::::;;;;;;i+nMWMWW
nnxxnnnxxxMMxxnnzzz#+i;;::,.....,,,,,,....`,,,::::::::,::;;;:,`,;;ii;iiiiiii***i;,,,,...``...,,,,:::::::::;;;;;;;i*zxMWMM
nxxxxnnxxxxMxMxnnzz#+*i;:,,,..,,,,,,,,.....,,::::::::::::;;;:,`:iiiiiii;;;iii*i;;,,,,,..``.....,,:::::::;;;;;;;;;i*#nxMWW
nxxnnxxxxxxMMxMnzz##+*i;:,,...,,,,::,.....,:::::::::::;;;ii;:,`:iiii;;;;;iiiii;;:::,:,..``.``..,:::::::;::;;;;;;;i*+zxxMW
nxnnnxxxxxxMMMxnnnzz#+*i;::,.`.,,:::,...,,:;::::::::::;;;i;;:.`,;;;;;;;;;;;iii;:;::,:...`````..,::::::::::;;;;;;;;*+#nMWM
nxxxxnxxxxxMMMMxxnz#+*i;;::,.``.,,,,...,,,:;::::::::;;;;;i;;:.`,:;;;;;;;;;;i;;;;:::::,,..````.,,,,,::::::::;;;;;ii*++znMM
nxxxnnnxxxxMMMMxnzz#+*i;;::,,.``..,....,:,:;::;;:::::;;;;i;;:..:;;;;:::;;;;;;;;;:,,::,,..```..,,,,,,,,::::::;;;iii*++##nM
nxxnnnnxxxMMWWWMxnz#+*i;;;:,,..``...`.,,::;;;:;;:::::;;;;;;;:.,:;;:::::;;;;;:::;;;:,,,,.`....,,,,,,,,:,,,::::;;;i*+##+#zn
xxxnxnxxxxMMWWMxnnzz#+*iii;:,..`......,::;;;;::;::;::;;;:;;;:,,:;:::::::;;;;;::;;;::,,,......,,,,::::,,,,,,:::;ii*++####z
xxxxxxxxxxMMWWWMxnnz##+*ii;:,,,....`.,,::;;;;;;i;;:::;:::;;::,,::::;:::::;;;:::;;;:;::,......,,,:::::,,,,,,::::;i*+++#znn
xnnxnnxxxxMMWWWWMxnzz+*i;:::,,,,,...,::::;;i;;;i;i;:::::::;:,.,:,,:;;::::;:::::;;;;::::,,....,,,::::,,,,,,,:::::i*++++#zx
xnnnxxxxxMMWW@@@Wxnz#+*ii;:,::::,,,,,:;;;;;;;;;;;i;:::,:,:::,`.,,,:;;::::;;:::::;;::,;;::,..,,:::::::,,,,,,,,:::;i*++++##
xnnxxxxxxMMWW@@@Wxnz#+**i;;::::::::::;;::;;::::::;:::,,:,:::.`.,,,:;;::::;;::::;;;,,,,:,,,,,,:::::::,,,,,,,,,:::;i***++#z
xxxxxxxxMMWWW@@WMnz##++***i::::::,:,:;:::;:::,,::;:::,,::::,.`.,,::;;:;:::;::::;:;:,,,:,,::::::::::,,,,,,,,,,:::;i****++#
xxxnxxxxMMWW@@@@Mnzzz##++*i:::::::,::;:;;;:,..,::::::,:::::,.`.,,::;;:;;:;:::::;:;:,,,,,:;;;::::::::,,...,,,,,::;i*****+#
xxxxxxxxMMWW@@WWMxnz##+++*ii;;;;;:,::::;;:,..,,::::::,::::,,.`.,,::;;::;;;::::;::::,,,,;::;;;;;;;;;:::,...,,,,,::;**i**++
xxxxxxxxMMWW@@WWxnzz##+++*i;iii;::::::;;:,..,::;;:::::::::,.``,,,,:;:::;;;:;::;::::::..:::;iiiii;;;::,,,.....,:::;iiii**+
xxxxxxMMMWW@@@WWxnnz##++*iiiiiiiii;;;;i;:...,:;;;:::::::,,,.``.,,,:::::;;:;;:;;::,,,::.,;iiiiiiii;::,,.......,,:::;iiii*+
xxxxxxMMMWWWW@WMxnzz##++**iiiiii*ii;;i;:,..,:;;;::::::;::,,.``.,,:::::;;;:;::;;:,,,,::,,:;ii;;;;ii;:,.``......,:::;iiii**
xxxxxxMMMWW@W@WMxnnzz###+***iii***i**i::..,:;;i;:::::::::,,.``.,,:::::;;;:;::;;,,,,,,:,,,::;i;;:::;:,,````....,:::;;iiii*
xxxxxMMMWWWW@@WMxnnzzzz#+**iiii*++**i;:,,::;iii;::::::::,:,.``..,:::::;;:;;::::,,:,,,,:,,,:;;;;;;:::,...`.....,,:::;iiii*
xxxxxxMMWWWWWWWMnnnnnz#+*iiiii***++*i:::;iiii*i;::::::::,,,..``,,::::;;::;;:::::,,:::,,:,:;;;;;;;;;:,,...```...,,::;;iiii
xxxxxMMMWWWWWWMxnnnzz#*****iii***++i;;iii****i;::::::,::,,...``.,,::::::::;:::::,:::::,,::;;iiii;;;:,..``````...,,,:iii;i
xxxxxMMWWWWWWWWxnnnz#+++++*++******iii*****i*i;::;::::,::,,..``.,::::::::::::::;,:,:::,,:;;iiiiii;::,..```````..,,,:;ii;;
xxxMMMWWWWW@WWMxnnzzz#zz#++++***i**ii*++***iii;::;;:::::,,,,.``,,,,::::::::::;::,,,::,:,:;;;iiiiii;:...```````...,,:;;i;;
xxxMMMWWWWW@WWMxnnnnnz#++###+++***ii*+++***iii;:;;;::,:::,,,,.`.:,,:::::::::::;:,,,,:,;::;;iiiiiii::,...`...``...,,,:;;ii
xxMMMMWWWWWWWWMxnnnnnz#znzz#++++*ii*+++****iii;;;;;;:::::,,:,..,:,:::::::::::::,.,.:::;;;::;ii;i;;:,,...,,,,.......,:;i;;
xxMMMWWW@@WWWWMnnnnnnnnzz#+++**+****++++***iiii;;i;;;;:;:::;:..,,,:::::::::::,,...,::,,,,,:iii;;;;:,:,.,:::,,,....,,:;iii
xxMMMWWW@@W@WMxnznnnnn##++##+++****++#++***iiii;;ii;ii;;;iii:..,,,::::,:::::,,,.,,,,,,,,,:;iii;;;;,,::,:,..........,,;ii;
xxMMMWWWWW@@WMxnnnnzzz########++***++#+***iiiiiiiiiiii;;iiii:...,:::::,:::::,,.,,,,,::::;;;;;;;;;;,,:::,.`` ```....,:;;;i
xxMMWWWW@@@WMxnnnnzzzz##+***++#+***++#+***iii;ii;iii;i;;iii;,..,,,:,::,:::,,,.,,,,,::::;i;ii;;;;;;,,:,:,.``  ```...,:;iii
xMMMWWWWWWWWMxxnzzzzzz##+*****++***++#+**iiii;;ii*i;;i;iiii:..,,,,:,:,::;:,,,.:,,,,,::;***iiii;:;:,,:,,,.```````...,:;i;;
xMMMWWWWWWWMMxnnnnzzzz#####*********+++*iiiii;;iii;;;ii;;;:,.,,.,,::::::;:,,,,::;;:,:;i++#*iii;::,,,,,,....`````...,,:i;;
xMMMWWWWWWWMMxnnnnzzz###++++********++**iiiiii;ii;;;i;;;;::,,,..,,::::;:;:,.,:;;;;;:;ii++z+i;i;::,,,,..,...``````..,,,;;;
xMMMWWW@WWMxnnnnzzzz###++++*+****i**+**iiiiiii;;;;;;;;;::,,,,,,,,,::;;;;;;,.,:;;;;;iii*##z+ii;:::,,....,.``` ```....,,:;i
xMMWWWW@@WMxxnzzzz####+++++++**i*i*++*iiiiiii;;;;;;;;;::,,,,,,,,,:::;;;;;;,,:;;::;;iii*#nz+*ii;::;:....,.```````....,,:;;
MMMWWWW@@WMxxnnzzzz###++###++**i*ii++***iiiii;;;;;;;;:::,,,,,,:::;::;;;;;:,,::::;i*i;i*#zz+*i;;:;:,.,,...```````....,,:;;
MMWWWWWWWMxxnnzzzzz##++++##++***iii*+**iiiiii;;;;i;;;::::,,,,:;;;::;;i;;;:,,,:,:;iii;i+##z#*i;;;;,:,:::...```````...,,:;;
MMWWWWWWMxxnnnzzzz##++##+++++++**ii*++*****iiiiiii;;;::::,,::;;;;;;;;;::::,:,,,,:;*ii**+#z#*ii;;;:;:;;;.````  ``....,,:;;