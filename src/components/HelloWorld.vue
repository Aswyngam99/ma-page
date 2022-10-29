<template>
    <div>
        <Navigation/>
      <v-card tile class="back" height ="200"></v-card>
   <!-- infos -->
          <v-card tile flat class="mx-6 my-6">
            <v-card class="mx-2 my-2 px-2 py-2">
                <h2 class="titre">1. Objet</h2>
                <p>Cette procédure décrit les étapes a suivre pour effectuer une analyse matiere active.</p>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2">
                <h2 class="titre">2. Domaine d'application</h2>
                <p>Cette procédure s’applique au laboratoire henkel reghaia.</p>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2">
                <h2 class="titre">3. Document de Référence</h2>
                 <v-list-item two-line>
                    <v-list-item-content>
                        <v-list-item-title><strong>- ISO 9000 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Principes essentiels et vocabulaire.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9001 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Exigences.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9002 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Lignes directrices pour l’application de l’ISO 9001:2015.</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2">
                <h2 class="titre">4. Définitions et Abréviations</h2>
                <p>MA : matière active.</p>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2">
                <h2 class="titre">5. Responsabilités et Autorités</h2>
                <p>Le technicien contrôle qualité est responsable sur l’analyse. <br> Le responsable laboratoire est responsable sur la validation des méthodes.</p>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2">
            <h2 class="titre">6. Processus</h2>
             <v-list-item two-line>
                <v-list-item-content>
                    <v-list-item-title><strong>1- Objectifs et applications</strong></v-list-item-title>
                    <v-list-item-subtitle>Cette méthode est utilisée pour déterminer le taux de tensioactifs anioniques (à l’exception des savons) dans les matières premières, les produits intermédiaires, les détergents liquides et en poudre ainsi que dans les produits d’entretien (sans bétaïne). Elle peut s’appliquer aux tensioactifs anioniques suivants:</v-list-item-subtitle>
                    <v-list-item-subtitle>- Alkylbenzol sulfonate C<sub>6</sub> et plus</v-list-item-subtitle>
                    <v-list-item-subtitle>- Alkyl sulfonates</v-list-item-subtitle>
                    <v-list-item-subtitle>- Alkyl sulfates C<sub>9</sub> et plus</v-list-item-subtitle>
                    <v-list-item-subtitle>- Alkyl éthersulfates</v-list-item-subtitle>
                    <v-list-item-subtitle>- Aminoéthyl sulfonates d´acide gras (= taurides d’acide gras)</v-list-item-subtitle>
                    <v-list-item-subtitle>- Iséthionates d´acide gras</v-list-item-subtitle>
                    <v-list-item-subtitle>Le méthylbenzol-, diméthylbenzol- ou 2-phénylpropyl sulfonate n’interfèrent pas si leur concentration se situe en deçà de 15 % de la teneur en tensioactif anionique et ne dépasse pas 5 % en <br> valeur absolue. Cette méthode ne s’applique pas aux éthersulfates d’alcool gras comprenant plus de 50 moles d’oxyde d’éthylène. <br> Le savon, les agents de complexion, les sels inorganiques comme le chlorure de sodium, le sulfate, le borate, le phosphate et le silicate ainsi que le peroxyde d’hydrogène <br> (peroxoborate, percarbonate) n’influencent pas le résultat. Le chlore disponible doit être décomposé avec du peroxyde d’hydrogène avant le titrage. <br> La masse molaire des tensioactifs anioniques à déterminer doit être connue. Si la matière première ou le produit contient plusieurs tensioactifs anioniques différents, la masse molaire <br> doit être calculée à partir des concentrations et du type de matière première.</v-list-item-subtitle>

                    <v-list-item-title><strong>2- Définitions et abréviations</strong></v-list-item-title>
                    <v-list-item-subtitle>Non indiqué.</v-list-item-subtitle>

                    <v-list-item-title><strong>3- Résumé de la méthode</strong></v-list-item-title>
                    <v-list-item-subtitle>On verse le trichlorométhane, la solution échantillon aqueuse acidifiée, un colorant cationique rouge (dimidium bromide) et un colorant anionique bleu (disulphine bleue) dans un récipient de <br> titrage à deux phases (voir notes). Le tensioactif réagit avec le colorant cationique, produisant la paire d’ions rouges correspondante, qui se déplace dans la couche de trichlorométhane sous <br> agitation de l’ensemble du mélange. <br> Au cours du titrage avec une solution mère de tensioactif cationique, le tensioactif anionique dans la phase de trichlorométhane lié au colorant cationique subit une réaction d’échange et <br> forme une paire d’ions incolore avec le tensioactif cationique. Lorsque le point d’équivalence est atteint, l’excédent de tensioactif cationique produit la paire d’ions correspondante avec le <br> colorant anionique. La paire d’ions est soluble dans le trichlorométhane. La solution de trichlorométhane devient grise avec une nuance bleue.</v-list-item-subtitle>

                    <v-list-item-title><strong>4- Réactifs</strong></v-list-item-title>
                    <v-list-item-subtitle>• Sel de dodecyl sulfate, standard primaire seulement, pour l’analyse du tensioactif; par ex. Merck 99,2 %</v-list-item-subtitle>
                    <v-list-item-subtitle>• Solution standard de hyamine, par ex. 0.005 M</v-list-item-subtitle>
                    <v-list-item-subtitle>• Acide sulfurique p. a., par ex. 10 %</v-list-item-subtitle>
                    <v-list-item-subtitle>• Trichlorométhane; par ex. de Merck</v-list-item-subtitle>
                    <v-list-item-subtitle>• Ethanol, 96 % p. a. ou isopropanol p. a. ou méthanol p. a.</v-list-item-subtitle>
                    <v-list-item-subtitle>• Dimidium bromide; par ex. de Merck</v-list-item-subtitle>
                    <v-list-item-subtitle>• Disulphine bleue VN 150; par ex. de Merck</v-list-item-subtitle>
                    <v-list-item-subtitle><strong>4.1 Préparation des réactifs de titrage</strong></v-list-item-subtitle>
                    <v-list-item-subtitle><strong>4.1.1 Préparation des réactifs de titrage</strong></v-list-item-subtitle>
                    <v-list-item-subtitle>• Remplir un ballon de 5000 ml jusqu’à moitié environ avec de l’eau déionisée et le placer dans un agitateur magnétique.</v-list-item-subtitle>
                    <v-list-item-subtitle>• Ajouter en mélangeant les réactifs suivants:</v-list-item-subtitle>
                    <v-list-item-subtitle>- 333 ±6 g (180 ±3 ml) de H<sub>2</sub>SO<sub>4</sub> 96% <strong>(doucement pour éviter les projections d’acide! Laisser refroidir jusqu’à température ambiante).</strong></v-list-item-subtitle>
                    <v-list-item-subtitle>- 500 ±5 ml de méthanol ou d’éthanol.</v-list-item-subtitle>
                    <v-list-item-subtitle>- 0.40 ±0.01 g de dimidium bromide.</v-list-item-subtitle>
                    <v-list-item-subtitle>- 0.20 ±0.01 g de disulphine bleue VN 150.</v-list-item-subtitle>
                    <v-list-item-subtitle>- Eau déionisée jusqu’à 5000 ml.</v-list-item-subtitle>
                    <v-list-item-subtitle>• Homogénéiser ce mélange pendant au moins 2 heures.</v-list-item-subtitle>
                    <v-list-item-subtitle>Ce mélange doit être stocké dans l’obscurité et/ou des bouteilles de verre marron. (La lumière du jour réduit la durée de vie du mélange).</v-list-item-subtitle>
                    <v-list-item-subtitle><strong>4.1.2 Dodecyl sulfate (standard primaire)</strong></v-list-item-subtitle>
                    <v-list-item-subtitle>Le dodecyl sulfate est utilisé sans séchage préalable. La valeur spécifiée sur la bouteille (par ex. 99,2 % pour le matériel Merck) est utilisée pour le calcul.</v-list-item-subtitle>
                    <v-list-item-subtitle><strong>4.1.3 Solution de dodecyl sulfate de sodium (exemple: 0.005 M)</strong></v-list-item-subtitle>
                    <v-list-item-subtitle>Prélever et peser 1,454 g ± 0,005 g de dodecyl sulfate de sodium (99,2 %) et les dissoudre dans env. 200 ml d’eau. Transvaser la solution dans un ballon gradué de 1000 ml et remplir ce dernier jusqu’à la marque avec de l’eau. La date de préparation de la solution doit être inscrite sur le ballon. <strong> La solution ne doit pas être utilisée après deux semaines (décomposition d’origine bactérienne possible).</strong> </v-list-item-subtitle>
                    <v-list-item-subtitle><strong>4.1.4 Détermination du facteur de titrage de la solution standard de hyamine (exemple: 0,05 M)</strong></v-list-item-subtitle>
                    <v-list-item-subtitle>	Pour analyser une solution de hyamine de 0,005 M standard, prélever avec une pipette 10,0 ml d’une solution de dodecyl sulfate de 0,005 M (voir 4.1.3) dans un ballon de titrage à deux phases et la titrer jusqu´au point d’équivalence comme décrit en 6.2. Répéter ce titrage trois fois et calculer le résultat moyen. Calculer le facteur de la solution de hyamine selon la formule suivante :</v-list-item-subtitle>
                    <v-list-item-subtitle>facteur <sub>(solution de hyamine)</sub> = <sup>10</sup>/ <sub>V <sub>Hy</sub> </sub> </v-list-item-subtitle>
                    <v-list-item-subtitle>	VHy = volume (en ml) de la solution de hyamine utilisée jusqu’à la valeur finale.</v-list-item-subtitle>
                     <v-list-item-subtitle><strong>Remarque générale : pour d’autres concentrations de hyamine, les quantités de réactifs doivent être ajustées.</strong> </v-list-item-subtitle>

                     <v-list-item-title><strong>5- Equipement</strong></v-list-item-title>
                     <v-list-item-subtitle>• Ballon de titrage à deux phases (voir 10).</v-list-item-subtitle>
                     <v-list-item-subtitle>• Agitateur à pâles en acier inoxydable; par ex. RW 20, Janke & Kunkel.</v-list-item-subtitle>
                     <v-list-item-subtitle>• Bouteille de stockage à doseurs pour le dosage du trichlorométhane, de l’acide sulfurique.</v-list-item-subtitle>
                     <v-list-item-subtitle>• Burette automatique, par ex. Dosimat, Metrohm.</v-list-item-subtitle>

                     <v-list-item-title><strong>6- Procédé</strong></v-list-item-title>
                     <v-list-item-subtitle><strong>6.1 Préparation de l’échantillon</strong></v-list-item-subtitle>
                     <v-list-item-subtitle>Prélever et peser la quantité requise de substance représentative homogénéisée (voir procédé en annexe) dans un verre gradué à bec. Ajouter de l’eau distillée bouillante. Puis, dissoudre l’échantillon dans un agitateur magnétique. Il est possible d’augmenter la solubilité, si nécessaire, en ajoutant env. 2 ml d’isopropanol ou d’un tensioactif non ionique à la solution bouillante. Dès que l’échantillon est complètement dissout, transvaser la solution dans un ballon gradué (volume K, voir formule en 7.1). Rincer les résidus du verre et de l’entonnoir et les transvaser dans le ballon avec de l’eau distillée. Puis, remplir le ballon jusqu’à la marque avec de l’eau distillée et homogénéiser la solution avec un agitateur magnétique.</v-list-item-subtitle>
                     <v-list-item-subtitle><strong>6.2 Titrage (détermination du surfactant anionique)</strong></v-list-item-subtitle>
                     <v-list-item-subtitle>Placer 15 ml de trichlorométhane dans le ballon de titrage à deux phases et ajouter une partie aliquote de la solution (voir 6.1) du ballon gradué ainsi que 10 ml du mélange indicateur (voir 4.1.1.). Mélanger les composants. Si le pH de la phase aqueuse dépasse 2, ajouter un peu d’acide sulfurique. Titrer l’échantillon jusqu’au point d’équivalence en ajoutant lentement la solution d’hyamine avec la burette automatique. Lorsque le titrage se rapproche du point d’équivalence, ajouter la solution d’hyamine au goutte-à-goutte. Après chaque addition et après avoir mélangé, contrôler la couleur de la phase de trichlorométhane. Lorsqu’on approche la valeur finale, l’émulsion eau / trichlorométhane initiale se sépare. La valeur finale est atteinte lorsque la phase de trichlorométhane ne présente plus aucune nuance rouge mais est légèrement teintée de bleu.</v-list-item-subtitle>
                     <v-list-item-title><strong>7- Calcul et indication du résultat</strong></v-list-item-title>
                     <v-list-item-subtitle><strong>7.1 Calcul</strong></v-list-item-subtitle>
                     <v-list-item-subtitle>	% de tensioactif anionique = (c * F * V * M * K / W * 1000 * P)*100</v-list-item-subtitle>
                     <v-list-item-subtitle>	c = molarité de la solution de hyamine [ M ]</v-list-item-subtitle>
                     <v-list-item-subtitle>	F = facteur de titrage de la solution de hyamine standard (voir 4.1.4)</v-list-item-subtitle>
                     <v-list-item-subtitle>	V = volume de solution de hyamine utilisé [ ml ]</v-list-item-subtitle>
                     <v-list-item-subtitle>	M = masse molaire moyenne du tensioactif anionique déterminé [ g/mole ]</v-list-item-subtitle>
                     <v-list-item-subtitle>	K = volume du ballon gradué utilisé pour la solution échantillon (voir 6.1) [ ml ]</v-list-item-subtitle>
                     <v-list-item-subtitle>	W = échantillon pesé [ g ]</v-list-item-subtitle>
                     <v-list-item-subtitle>	P = volume de solution échantillon prélevé à la pipette (voir 6.2) [ ml ]</v-list-item-subtitle>
                     <v-list-item-subtitle>	* En fonction de la teneur en tensioactif anionique, le poids de la solution échantillon devrait être choisi de telle sorte que la quantité d’hyamine permettant d’atteindre le point d’équivalence se situe entre 4 et 10 ml.</v-list-item-subtitle>
                     <v-list-item-subtitle>	La masse molaire moyenne réelle des tensioactifs anioniques utilisés dans un produit fini ou intermédiaire doit être calculée à partir des données fournies dans la formule de cette substance.</v-list-item-subtitle>
                     <v-list-item-subtitle><strong>7.2 Indication du résultat</strong></v-list-item-subtitle>
                     <v-list-item-subtitle>	Le résultat est indiqué dans cette méthode en pourcentage, au dixième près, et indique la masse moléculaire du tensioactif utilisé pour le calcul. <br> Les produits dont la base tensioactive n’est pas connue ne peuvent être analysés de façon précise avec cette méthode. Si on analyse ce type de produits, cela doit être indiqué clairement (par ex. "tensioactif anionique, évalué en tant qu’acide sulfonique d’alkylbenzol, MW 320: x%, mais non identifié comme tel.")</v-list-item-subtitle>

                     <v-list-item-title><strong>8- Précision</strong></v-list-item-title>
                     <v-list-item-subtitle>	Nous avons indiqué ci-dessous les résultats d´un test réalisé dans différents laboratoires (QCLs, TTA) avec le même lot d’acide sulfonique d’alkylbenzol :</v-list-item-subtitle>
                     <v-simple-table>
                        <template v-slot:default>
                            <thead>
                            <tr>
                                <th class="text-left"> 	Laboratoires </th>
                                <th class="text-left"> 	1 </th>
                                <th class="text-left"> 	2 </th>
                                <th class="text-left "> 3 </th>
                                <th class="text-left"> 	4 </th>
                                <th class="text-left"> 	5 </th>
                                <th class="text-left"> 	6 </th>
                                <th class="text-left"> 	7 </th>
                            </tr>
                         </thead>
                         <tbody>
                            <tr>
                                <td> Nombre de mesures N </td>
                                <td> 10 </td>
                                <td> 5 </td>
                                <td> 7 </td>
                                <td> 10 </td>
                                <td> 10 </td>
                                <td> 6 </td>
                                <td> 10 </td>
                            </tr>
                            <tr>
                                <td> Valeur moyenne [ % ] </td>
                                <td> 96.06 </td>
                                <td> 96.00 </td>
                                <td> 96.31 </td>
                                <td> 96.84 </td>
                                <td> 97.77 </td>
                                <td> 96.13 </td>
                                <td> 96.09 </td>
                            </tr>
                            <tr>
                                <td> Ecart standard σn-1 [ % ] </td>
                                <td> 0.25 </td>
                                <td> 0.14 </td>
                                <td> 0.09 </td>
                                <td> 0.32 </td>
                                <td> 0.23 </td>
                                <td> 0.32 </td>
                                <td> 0.22 </td>
                            </tr>
                            <tr>
                                <td> Coefficient de variation V [ % rel. ]</td>
                                <td> 0.26 </td>
                                <td> 0.15 </td>
                                <td> 0.09 </td>
                                <td> 0.33 </td>
                                <td> 0.24 </td>
                                <td> 0.33 </td>
                                <td> 0.23 </td>
                            </tr>
                        </tbody>
                        </template>
                     </v-simple-table>
                    <v-list-item-title><strong>9- Sécurité</strong></v-list-item-title>
                    <v-list-item-subtitle>
                    <v-row>
                        <v-col cols="4" md="3">
                            Acide sulfurique, 10 % 
                        </v-col>
                        <v-col cols="4" md="3">
                            irritant <br> R: 36/38 <br> S: 2-26
                        </v-col>
                    </v-row>

                    <v-row>
                        <v-col cols="4" md="3">
                            Trichlorométhane 
                        </v-col>
                        <v-col cols="4" md="3">
                            dangereux <br> R : 22-38-40-48/20/22 <br> S: 36/37
                        </v-col>
                    </v-row>

                    <v-row>
                        <v-col cols="4" md="3">
                            Ethanol 
                        </v-col>
                        <v-col cols="4" md="3">
                            très inflammable <br> R : 11 <br> S: (2)-7-16
                        </v-col>
                    </v-row>

                     <v-row>
                        <v-col cols="4" md="3">
                            Méthanol 
                        </v-col>
                        <v-col cols="4" md="3">
                            très inflammable <br> R : 11-23/25 <br> S: (1/2)-7-16-24-25
                        </v-col>
                    </v-row>

                    <v-row>
                        <v-col cols="4" md="3">
                            Isopropanol
                        </v-col>
                        <v-col cols="4" md="3">
                            très inflammable <br> R : 11 <br> S: (2)-7-16
                        </v-col>
                    </v-row>

                     <v-row>
                        <v-col cols="4" md="3">
                            Hyamine
                        </v-col>
                        <v-col cols="4" md="3">
                            dangereux <br> R : 22-36/38
                        </v-col>
                    </v-row>

                      <v-row>
                        <v-col cols="4" md="3">
                            Dimidium bromide
                        </v-col>
                        <v-col cols="4" md="3">
                            irritant <br> R : 36/37/38 <br> S: 22-26-28
                        </v-col>
                    </v-row>
                	Pour plus d’informations, veuillez vous reporter aux consignes de sécurité locales.
                    </v-list-item-subtitle>
                    <v-list-item-title><strong>10- Remarques</strong></v-list-item-title>
                    <v-list-item-subtitle>•	La méthode correspond à DGF H III-10 (94).</v-list-item-subtitle>
                    <v-list-item-subtitle>•	Description du ballon de titrage à deux phases : <br> A.R. Hoffmann, W.W. Böer, G.W.G. Schwarz; Fette Seifen Anstrichmittel, No.9, (1976), p. 367 et suivantes.</v-list-item-subtitle>
                </v-list-item-content>
            </v-list-item>
            </v-card>
           </v-card>
             <!-- Footer -->
            <v-footer flat bottom padless>
                <v-col><strong>PR SHEQ VR A.5-01– Procédure de Veille Réglementaire</strong> <br> <div class="primary--text"> Propriété exclusive de HENKEL Algérie Unité de Production Réghaia. <br> Toute reproduction intégrale ou partielle ainsi que son utilisation par, ou la communication à, des tiers, sans accord préalable écrit de l’auteur est illicite.</div> Le R-SMI est responsable de la gestion et l’application de cette procédure.</v-col>
            </v-footer>
    </div>
</template>
<script>
import Navigation from '@/components/Navigation.vue'
export default({
 components: {Navigation},
 data () {
      return {
        things: [
          {
            Enregistrement: 'Fiche de suivi incident qualité',
            Code: 'SD SHEQ TNC 4.3.12-10',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          }
        ]
      }
    },
})
</script>
<style scoped>
.back{
   background: url('../../public/labo3.jpg');
}
.v-tabs-bar {
    float: left !important;
}
.v-tab {
    text-transform: none !important;
}
.lol:hover {
    background:#96030d ;
  }
.list{
    color: #e6e7e7;
}
.titre{
  color: #ff0011;
}
.tab{
  background-color: #fa3722;
}
</style>