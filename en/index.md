---
layout: default
title: (EN) Outil de catégorisation de l’information 
lang: en
---

<div class="container">
    <div id="alertMessage"></div>
    <div class="row">
        <main property="mainContentOfPage" class="col-md-9 col-md-push-3" typeof="WebPageElement">
            <h1 property="name" id="wb-cont">
                <tvar data-tvar="fr_title">Outil de catégorisation de l’information</tvar>
            </h1>
            <tvar data-tvar="fr_content">
                <p>La protection de l'information englobe non seulement le traitement et la protection appropriés de l'information en soi, mais aussi le maintien de cette protection depuis la création de l'information jusqu'à son élimination en passant par son stockage. Les employés doivent protéger tous les renseignements, qu'ils soient sous forme physique ou électronique. Ce guide vous permet de trouver facilement tous les renseignements dont vous avez besoin pour la catégorisation et le traitement de l'information. Il existe deux niveaux d'informations sensibles, Classifiée et Protégée, qui ont chacun 3 catégories.</p>
                <h2>Information classifiée</h2>
                <p>Concerne l'intérêt national. Elle concerne la défense et le maintien de la stabilité sociale, politique et économique du Canada et pourrait faire l'objet d'une exemption ou d'une exclusion en vertu de la _Loi sur l'accèss à l'information_.</p>

<!-- 
INFORMATION CLASSIFIÉE
-->
<div id="details-elements">
    <div class="btn-group mrgn-bttm-md">
        <button type="button" class="btn btn-default wb-toggle" data-toggle="{&quot;selector&quot;: &quot;details&quot;, &quot;parent&quot;: &quot;#details-elements&quot;, &quot;type&quot;: &quot;on&quot;, &quot;print&quot;: &quot;on&quot;}">Agrandir tout</button> <button type="button" class="btn btn-default wb-toggle" data-toggle="{&quot;selector&quot;: &quot;details&quot;, &quot;parent&quot;: &quot;#details-elements&quot;, &quot;type&quot;: &quot;off&quot;}">Réduire tout</button>
    </div>

    <ul id="classifiee" class="list-unstyled wb-filter">
        <li class="mrgn-tp-sm">
            <details id="confidentiel_" onclick="shwHidden(this.id)">
                <summary class="btn-default">
                    <span id="confidentiel" aria-level="3" role="heading">Confidentiel</span>
                </summary>
                <h4><span class="wb-inv">Confidentiel </span>Définition :</h4>
                <p>Renseignements dont la divulgation non autorisée peut causer un préjudice limité à l'intérêt national.</p>
                <h4><span class="wb-inv">Confidentiel </span>Exemples :</h4>
            <ul>
                <li>Affaires internationales, interprovinciales/territoriales et défense</li>
                <li>Informations diplomatiques</li>
                <li>Délibérations officielles</li>
                <li>Propositions de financement ou notes d'information sur des questions liées à l'intérêt national canadien qui, si elles étaient compromises, affecteraient l'intérêt national de manière limitée ou modérée</li>
            </ul>
            <h4><span class="wb-inv">Confidentiel </span>Filtrage de sécurité requis :</h4>
            <p>Secret</p>
            <p>Note : En plus d'avoir un filtrage de sécurité valide, la personne doit également respecter le &laquo; principe du besoin de savoir/besoin d'accès &raquo;, c'est-à-dire pour ceux dont les fonctions exigent un tel accès.</p>
            <div class="alert alert-info">
                <p><a href="/fra/si/securite/categorisation/activite_confidential.shtml"><strong>Que voulez-vous faire avec l'information confidentielle ?</strong></a></p>
            </div>
            </details>
        </li>
        <li>
            <details id="secret_" onclick="shwHidden(this.id)">
                <summary class="btn-default">
                    <span id="secret" aria-level="3" role="heading">Secret</span>
                </summary>
                <h4><span class="wb-inv">Secret </span>Définition :</h4>
                <p>Renseignements dont la divulgation non autorisée pourrait entra&icirc;ner un accroissement des tensions internationales, ou un préjudice grave au regard des responsabilités ministérielles, des relations internationales ou des relations fédérales-provinciales, d'opérations de renseignement importantes, de l'ordre civil, etc.</p>
                <h4><span class="wb-inv">Secret </span>Exemples :</h4>
                <ul>
                    <li>Procès-verbaux ou comptes rendus des discussions du Cabinet ou des comités du Cabinet se rapportant à des responsabilités ministérielles (p. ex. mémoires au Cabinet);</li>
                    <li>Autres renseignements classifiés provenant du Bureau du Conseil privé (BCP) ou du cabinet d'un ministre</li>
                    <li>Discussions entre l'administration fédérale, les provinces et les territoires;</li>
                    <li>Dossiers portant sur des consultations et des négociations en cours entre le Ministère et ses homologues provinciaux/territoriaux à propos de modifications importantes à des stratégies nationales en matière d'emploi;</li>
                    <li>Information fournie par le Ministère aux fins du budget national avant la publication officielle de ce dernier;</li>
                    <li>Versions préliminaires de lois et de stratégies envisages.</li>
                </ul>
                <h4><span class="wb-inv">Secret </span>Filtrage de sécurité requis :</h4>
                <p>Secret.</p>
                <p><strong>Note</strong> : En plus d'avoir un filtrage de sécurité valide, la personne doit également respecter le &laquo; principe du besoin de savoir/besoin d'accès &raquo;, c'est-à-dire pour ceux dont les fonctions exigent un tel accès.</p>
                <div class="alert alert-info">
                    <p><a href="/fra/si/securite/categorisation/activite_secret.shtml"><strong>Que voulez-vous faire avec l'information secrète ?</strong></a></p>
                </div>
            </details>
        </li>
        <li>
            <details id="tres-secret_" onclick="shwHidden(this.id)">
                <summary class="btn-default">
                    <span id="tres-secret" aria-level="3" role="heading">Très secret</span>
                </summary>
                <h4><span class="wb-inv">Très secret </span>Définition :</h4>
                <p>Renseignements dont la compromission pourrait entra&icirc;ner de nombreuses pertes de vie, un préjudice très grave au regard d'opérations de sécurité et de renseignement extrêmement importantes, des actes de violence armée à l'endroit du Canada ou de ses alliés, ou des actes de terrorisme (par exemple, le terrorisme).</p>
                <h4><span class="wb-inv">Très secret </span>Exemples :</h4>
                <ul>
                    <li>Nombreuse pertes de vie</li>
                    <li>Perte de continuité du gouvernement</li>
                    <li>Atteinte à l'efficacité de la sécurité des forces canadiennes ou alliées.</li>
                </ul>
                <h4><span class="wb-inv">Très secret </span>Filtrage de sécurité requis :</h4>
                <p>Très Secret</p>
                <p><strong>Note</strong> : En plus d'avoir un filtrage de sécurité valide, la personne doit également respecter le &laquo; principe du besoin de savoir/besoin d'accès &raquo;, c'est-à-dire pour ceux dont les fonctions exigent un tel accès.</p>
                <div class="alert alert-info">
                    <p><a href="/fra/si/securite/categorisation/activite_tres_secret.shtml"><strong>Que voulez-vous faire avec l'information très secrète ?</strong></a></p>
                </div>
            </details>
        </li>
    </ul>
</div>

<!-- 
INFORMATION PROTÉGÉE
-->

<h2>Information protégée</h2>
<p>Se réfère à des dispositions spé;cifiques de la Loi sur l'accès à l'information et de la Loi sur la protection de la vie privé;e et s'applique aux informations personnelles, privé;es et commerciales sensibles qui peuvent bé;né;ficier d'une exemption ou d'une exclusion.</p>
<div id="elements-protegee">
    <div class="btn-group mrgn-bttm-md">
        <button type="button" class="btn btn-default wb-toggle" data-toggle="{&quot;selector&quot;: &quot;details&quot;, &quot;parent&quot;: &quot;#elements-protegee&quot;, &quot;type&quot;: &quot;on&quot;, &quot;print&quot;: &quot;on&quot;}">Agrandir tout</button> <button type="button" class="btn btn-default wb-toggle" data-toggle="{&quot;selector&quot;: &quot;details&quot;, &quot;parent&quot;: &quot;#elements-protegee&quot;, &quot;type&quot;: &quot;off&quot;}">Réduire tout</button>
    </div>
    <ul id="protegee" class="list-unstyled wb-filter">
        <li class="mrgn-tp-sm">
            <details id="protege-a_" onclick="shwHidden(this.id)">
                <summary class="btn-default">
                    <span id="protege-a" aria-level="3" role="heading">Protégé A</span>
                </summary>
                <h4><span class="wb-inv">Protégé A </span>Définition :</h4>
                <p>Renseignement dont la divulgation non autorisée peut causer un préjudice à des intérêts privés ou non nationaux, à un particulier ou à une entreprise, telle que la perte de la vie privée ou un embarras.</p>
                <h4><span class="wb-inv">Protégé A </span>Exemples :</h4>
                <h5>Document contenant un des éléments suivants:</h5>
                <ul>
                    <li>Nom complet</li>
                    <li>Date de naissance (DDN)</li>
                    <li>Adresse de courriel personnel</li>
                </ul>
                <h5><span class="wb-inv">Protégé A </span>Activités ministérielles :</h5>
                <div class="mrgn-lft-lg">
                    <p>Contrats, offres à commandes, la plupart des courriels au sein de l'organisation</p>
                </div>
                <h4><span class="wb-inv">Protégé A </span>Filtrage de sécurité requis :</h4>
                <p>Fiabilité</p>
                <p><strong>Note</strong> : En plus d'avoir un filtrage de sécurité valide, la personne doit également respecter le &laquo; principe du besoin de savoir/besoin d'accès &raquo;, c'est-à-dire pour ceux dont les fonctions exigent un tel accès.</p>
                <div class="alert alert-info">
                    <p><a href="/fra/si/securite/categorisation/activite_A.shtml"><strong>Que voulez-vous faire avec l'information Protégé A ?</strong></a></p>
                </div>
            </details>
        </li>
        <li>
            <details id="protege-b_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="protege-b" aria-level="3" role="heading">Protégé B</span></summary>
                <h4><span class="wb-inv">Protégé B </span>Définition :</h4>
                <p>Renseignement dont la divulgation non autorisée peut causer un préjudice grave à des intérêts privés ou non nationaux, à un particulier ou à une entreprise, telle que la perte de la vie privée ou un embarras.</p>
                <h4><span class="wb-inv">Protégé B </span>Exemples :</h4>
                <h5>Si le document contient un nom complet avec un de ces éléments:</h5>
                <ul>
                    <li>Date de naissance (DDN)</li>
                    <li>Genre</li>
                    <li>Renseignements médicaux ou financiers</li>
                    <li>état civil</li>
                </ul>
                <h5><span class="wb-inv">Protégé B </span>Un seul de ces éléments est Protégé B:</h5>
                <ul>
                    <li>Numéro d'assurance sociale (NAS)</li>
                    <li>Code d'identification de dossier personnel (CIDP)</li>
                    <li>Tout numéro associé exclusivement à une personne</li>
                </ul>
                <h5><span class="wb-inv">Protégé B </span>Activités ministérielles:</h5>
                <ul>
                    <li>Plans de continuité des affaires (PCA);</li>
                    <li>Plans d'étage (y compris les systèmes de sécurité et les zones à accès réglementé [par exemple: pièces sécurisées])</li>
                    <li>Renseignements commerciaux de tiers fournis à titre confidentiel (par exemple: numéro d'entreprise de l'employeur ou de la compagnie)</li>
                    <li>Renseignements de nature juridique (secret professionnel)</li>
                </ul>
                <h4><span class="wb-inv">Protégé B </span>Filtrage de sécurité requis :</h4>
                <p>Fiabilité</p>
                <p><strong>Note</strong> : En plus d'avoir un filtrage de sécurité valide, la personne doit également respecter le &laquo; principe du besoin de savoir/besoin d'accès &raquo;, c'est-à-dire pour ceux dont les fonctions exigent un tel accès.</p>
                <div class="alert alert-info">
                    <p><a href="/fra/si/securite/categorisation/activite_B.shtml"><strong>Que voulez-vous faire avec l'information Protégé B ?</strong></a></p>
                </div>
            </details>
        </li>
        <li>
            <details id="protege-c_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="protege-c" aria-level="3" role="heading">Protégé C </span></summary>
                <h4><span class="wb-inv">Protégé C </span>Définition :</h4>
                <p>Renseignements de nature très délicate non liés à l'intérêt national qui a) peuvent être admissibles à une exemption ou à une exclusion en vertu de la Loi sur la protection des renseignements personnels ou de la Loi sur l'accès à l'information, et b) dont on peut raisonnablement penser que la divulgation non autorisée risque de causer un préjudice très grave à une personne, une organisation ou un gouvernement.</p>
                <h4><span class="wb-inv">Protégé C </span>Exemples :</h4>
                <ul>
                    <li>Enquêtes (menaces pesant sur des particuliers)</li>
                    <li>Informateurs de la police</li>
                    <li>Programme de protection des témoins</li>
                    <li>Nom d'un informateur</li>
                    <li>Opérations secrètes des services de police</li>
                </ul>
                <h5><span class="wb-inv">Protégé C </span>Activités ministérielles :</h5>
                <div class="mrgn-lft-lg">
                <p>Secret industriel, renseignements commerciaux fournis par un tiers, etc.</p>
            </div>
            <h4><span class="wb-inv">Protégé C </span>Filtrage de sécurité requis :</h4>
            <p>Secret</p>
            <p><strong>Note</strong> : En plus d'avoir un filtrage de sécurité valide, la personne doit également respecter le &laquo; principe du besoin de savoir/besoin d'accès &raquo;, c'est-à-dire pour ceux dont les fonctions exigent un tel accès.</p>
            <div class="alert alert-info">
                <p><a href="/fra/si/securite/categorisation/activite_C.shtml"><strong>Que voulez-vous faire avec l'information Protégé C ?</strong></a></p>
            </div>
            </details>
        </li>
    </ul>
</div>

<!-- 
INFORMATION NON CLASSIFIÉE
-->

<h2 id="non-classifiee">Information non classifiée</h2>
<p>Information qui ne porte pas atteinte aux intérêts personnels, industriels ou gouvernementaux.</p>
<h2>Catégorie désignée par secteur d'activité des documents</h2>
<p>Sélectionnez le secteur d'activité de votre document et trouvez des exemples d'informations avec leurs catégories désignées.</p>
<div id="elements-business">
    <div class="btn-group mrgn-bttm-md">
        <button type="button" class="btn btn-default wb-toggle" data-toggle="{&quot;selector&quot;: &quot;details&quot;, &quot;parent&quot;: &quot;#elements-business&quot;, &quot;type&quot;: &quot;on&quot;, &quot;print&quot;: &quot;on&quot;}">Agrandir tout</button> <button type="button" class="btn btn-default wb-toggle" data-toggle="{&quot;selector&quot;: &quot;details&quot;, &quot;parent&quot;: &quot;#elements-business&quot;, &quot;type&quot;: &quot;off&quot;}">Réduire tout</button>
    </div>
    <ul id="entreprise-lignes" class="list-unstyled wb-filter">
        <li class="mrgn-tp-sm">
            <details id="gestion-locaux_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="gestion-locaux" aria-level="3" role="heading">Gestion des locaux</span></summary>
                <h4><span class="wb-inv">Gestion des locaux </span>Protégé A:</h4>
            <ul>
                <li>Contrats</li>
                <li>Plan d'étage (aménagement seulement)</li>
            </ul>
            <h4><span class="wb-inv">Gestion des locaux </span>Protégé B :</h4>
            <ul>
                <li>Analyse des risques liés aux infrastructures essentielles</li>
                <li>Plan d'étage (y compris les panneaux d'alarme, les pièces à accès réglementé, le c&acirc;blage de sécurité, etc.)</li>
                <li>Norme de design d'intérieur (identité des pièces et du contenu sécurisés, systèmes de sécurité, etc.)</li>
            </ul>
            </details>
        </li>
        <li>
            <details id="AIPRP_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="AIPRP" aria-level="3" role="heading">AIPRP</span></summary>
                <ul class="list-unstyled">
                    <li>
                        <details id="_" onclick="shwHidden(this.id)">
                            <summary><span aria-level="4" role="heading">Accès à l'information (AI)</span></summary>
                            <h5><span class="wb-inv">Accès à l'information </span>Non classifié:</h5>
                            <ul>
                                <li>Matériel de formation et d'orientation concernant l'AIPRP</li>
                                <li>Rapports internes et externes</li>
                            </ul>
                            <h5><span class="wb-inv">Accès à l'information </span>Protégé A:</h5>
                            <ul>
                                <li><span class="wb-inv">Accès à l'information </span>Contenu des demandes d'AIPRP</li>
                                <li>Contenu du règlement des plaintes en matière d'AIPRP</li>
                                <li>Lettres de consultation avec les parties prenantes internes et externes</li>
                            </ul>
                            <h5><span class="wb-inv">Accès à l'information </span>Secret:</h5>
                            <div class="mrgn-lft-lg">
                                <p>Contenu des documents confidentiels du Cabinet en consultation avec les Services juridiques</p>
                            </div>
                        </details>
                    </li>
                    <li>
                        <details id="confidentialite_" onclick="shwHidden(this.id)">
                            <summary><span id="confidentialite" aria-level="4" role="heading">Confidentialité</span></summary>
                            <h5><span class="wb-inv">Confidentialité </span>Non classifié :</h5>
                            <div class="mrgn-lft-lg">
                                <p>Matériel de formation et d'orientation</p>
                            </div>
                            <h5><span class="wb-inv">Confidentialité </span>Protégé B:</h5>
                            <ul>
                                <li>évaluations de la confidentialité/analyse de nouveaux programmes/initiatives/solutions ou systèmes</li>
                                <li>Dossiers d'enquête sur les atteintes à la vie privée et lettres aux clients touchés par une atteinte à la vie privée</li>
                                <li>Plaintes relatives à la confidentialité concernant le traitement des renseignements personnels par EDSC</li>
                            </ul>
                            <h5><span class="wb-inv">Confidentialité </span>Divers:</h5>
                            <ul>
                                <li>Conseils de confidentialité aux programmes concernant le traitement des informations personnelles (portée : non classifié à Protégé B)</li>
                                <li>Recommandations en matière de confidentialité concernant les clauses à inclure dans les contrats, les présentations au Conseil du Trésor et les présentations au Cabinet (portée : Protégé de B à Secret)</li>
                            </ul>
                        <p class="mrgn-tp-md">Consultez les experts en matière d'AIPRP pour confirmer la catégorisation</p>
                        </details>
                    </li>
                </ul>
            </details>
        </li>
        <li>
            <details id="risques_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="risques" aria-level="3" role="heading">Audit et gestion des risques d'entreprise </span></summary>
                <ul class="list-unstyled">
                    <li>
                        <details id="audit_" onclick="shwHidden(this.id)">
                            <summary><span id="audit" aria-level="4" role="heading">Audit (interne et externe)</span></summary>
                            <ul>
                                <li>Plans d'audit axés sur les risques</li>
                                <li>Rapports d'audit</li>
                                <li>Réponses aux audits externes</li>
                                <li>Plans d'action de la direction</li>
                            </ul>
                            <p class="mrgn-tp-md">Consultez les experts en matière d'Audit et gestion des risques d'entreprise pour confirmer la catégorisation.</p>
                        </details>
                    </li>
                    <li>
                        <details id="gestion-risques_" onclick="shwHidden(this.id)">
                            <summary><span id="gestion-risques" aria-level="4" role="heading">Gestion des risques</span></summary>
                            <ul>
                                <li>Registres des risques des directions générales</li>
                                <li>Profil de risque du ministère (rapport PRM)</li>
                                <li>Analyses et recherches environnementales</li>
                                <li>Politique de gestion intégrée du risque (GIR)</li>
                                <li>évaluations des risques</li>
                            </ul>
                            <p class="mrgn-tp-md">Consultez les experts en matière d'Audit et gestion des risques d'entreprise pour confirmer la catégorisation.</p>
                        </details>
                    </li>
                </ul>
            </details>
        </li>
        <li>
            <details id="citoyens_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="citoyens" aria-level="3" role="heading">Direction générale de service aux citoyens </span></summary>
                <h4><span class="wb-inv">Direction générale de service aux citoyens </span>Protégé B :</h4>
                <div class="mrgn-lft-lg">
                    <p>Relevé d'emploi</p>
                </div>
                <h4><span class="wb-inv">Direction générale de service aux citoyens </span>Secret:</h4>
                <div class="mrgn-lft-lg">
                    <p>Passeports vierges</p>
                </div>
            </details>
        </li>
        <li>
            <details id="finances_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="finances" aria-level="3" role="heading">Finances</span></summary>
                <h4><span class="wb-inv">Finances </span>Protégé B:</h4>
                <ul>
                    <li>Solvabilité</li>
                    <li>Antécédents financiers, activités financières ou solvabilité</li>
                    <li>Renseignements relatifs aux demandes de financement</li>
                    <li>Propositions de financement soumises par les provinces</li>
                    <li>Solde bancaire d'un particulier</li>
                    <li>Opérations financières et paiements importants</li>
                    <li>Présentations au Conseil du Trésor - Financement des programmes (lorsqu'il n'est pas dans l'intérêt national ; par exemple, programmes existants; tels que, mais sans s'y limiter : AE, RPC, SV, etc.)</li>
                </ul>
                <h4><span class="wb-inv">Finances </span>Secret:</h4>
                <div class="mrgn-lft-lg">
                    <p>Présentations au Conseil du Trésor de nature financière - Secret lorsqu'il est dans l'intérêt national (par exemple, un financement demandé sur la base d'une nouvelle planification budgétaire et/ou d'un nouveau programme qui n'est pas encore accessible au public).</p>
                </div>
            </details>
        </li>
        <li>
            <details id="rh_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="rh" aria-level="3" role="heading">Ressources humaines</span></summary>
                <ul class="list-unstyled">
                    <li>
                        <details id="dotation_" onclick="shwHidden(this.id)">
                            <summary><span id="dotation" aria-level="4" role="heading">Dotation</span></summary>
                            <h5><span class="wb-inv">Dotation </span>Protégé B :</h5>
                            <ul>
                                <li>Dossier personnel d'employé</li>
                                <li>Plans de dotation, conseils et orientation</li>
                                <li>Informations sur le processus de sélection, y compris les dossiers d'évaluation des candidats contenant les résultats des tests et les communications</li>
                                <li>Détails de l'obligation d'accommodement dans le contexte de l'évaluation</li>
                                <li>Toute autre information relative au processus de sélection qui pourrait être pertinente</li>
                                <li>Détails des plaintes relatives à la dotation, y compris les conseils et les orientations et les actions proposées</li>
                                <li>Détails des enquêtes de dotation, y compris les conseils et les orientations et les actions proposées</li>
                                <li>Détails des plaintes à la Commission canadienne des droits de la personne, y compris des conseils, des orientations et des mesures proposées</li>
                                <li>Détails des plaintes relatives aux langues officielles, y compris les conseils et l'orientation et les mesures proposées</li>
                                <li>Ententes conclues dans le cadre d'un recours (ex : entente de médiation)</li>
                                <li>évaluations de rendement</li>
                            </ul>
                            <h5><span class="wb-inv">Dotation </span>Divers :</h5>
                            <div class="mrgn-lft-lg">
                                <p>Offre (lettre ou contrat) d'emploi - Protégé A si l'offre ne contient pas de CIDP ; si un CIDP est indiqué, il est par défaut Protégé B.</p>
                            </div>
                        </details>
                    </li>
                    <li>
                        <details id="sst_" onclick="shwHidden(this.id)">
                            <summary><span id="sst" aria-level="4" role="heading">Santé et sécurité au travail</span></summary>
                            <h5><span class="wb-inv">Santé et sécurité au travail </span>Protégé B</h5>
                            <ul>
                                <li>Informations fournissant des détails sur un incident sur le lieu de travail</li>
                                <li>Contenu de rapports d'évaluation médicale</li>
                                <li>Détails des incidents de violence au travail</li>
                                <li>Informations détaillées sur les limitations fonctionnelles d'une personne</li>
                                <li>Contenu d'un rapport d'évaluation ergonomique</li>
                            </ul>
                        </details>
                    </li>
                    <li>
                        <details id="travail_" onclick="shwHidden(this.id)">
                            <summary><span id="travail" aria-level="4" role="heading">Relations de travail</span></summary>
                            <h5><span class="wb-inv">Relations de travail </span>Protégé B :</h5>
                            <ul>
                                <li>Détails du grief et actions proposées</li>
                                <li>Détails des plaintes à la Commission canadienne des droits de la personne</li>
                                <li>Détails des plaintes de harcèlement</li>
                                <li>Contenu / détails des rapports médicaux, psychiatriques ou psychologiques</li>
                                <li>Mesures disciplinaires</li>
                            </ul>
                        </details>
                    </li>
                    <li>
                        <details id="ve_" onclick="shwHidden(this.id)">
                            <summary><span id="ve" aria-level="4" role="heading">Valeurs et éthique</span></summary>
                            <h5><span class="wb-inv">Valeurs et éthique </span>Protégé B:</h5>
                            <ul>
                                <li>Conflits d'intérêt</li>
                                <li>Contenu des lettres de plaintes</li>
                                <li>Contenu d'investigations</li>
                            </ul>
                        </details>
                    </li>
                </ul>
            </details>
        </li>
        <li>
            <details id="divulgation-interne_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="divulgation-interne" aria-level="3" role="heading">Divulgation à l'interne </span></summary>
                <p>Informations relatives à une enquête sur un acte répréhensible présumé en milieu de travail.</p>
                <p>Consultez les experts en matière de divulgation à l'interne pour confirmer la catégorisation</p>
            </details>
        </li>
        <li>
            <details id="juridiques_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="juridiques" aria-level="3" role="heading">Services juridiques</span></summary>
                <h4><span class="wb-inv">Services juridiques </span>Protégé B :</h4>
                <div class="mrgn-lft-lg">
                    <p>Information assujettie au secret professionnel de l'avocat</p>
                </div>
            </details>
        </li>
        <li>
            <details id="ombudsman_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="ombudsman" aria-level="3" role="heading">Ombudsman</span></summary>
                <h4><span class="wb-inv">Ombudsman </span>Protégé B :</h4>
                <div class="mrgn-lft-lg">
                    <p>Plaintes</p>
                </div>
            </details>
        </li>
        <li>
            <details id="securite_" onclick="shwHidden(this.id)">
                <summary class="btn-default"><span id="securite" aria-level="3" role="heading">Sécurité</span></summary>
                <h4><span class="wb-inv">Sécurité </span>Protégé B :</h4>
                <ul>
                    <li>Documents d'autorisation de sécurité</li>
                    <li>Renseignements détaillés sur des rapports d'enquête</li>
                    <li>Précisions sur une évaluation de la menace et des risques (EMR)</li>
                    <li>Précisions à propos de rapports sur des cas d'atteinte à la sécurité</li>
                    <li>Précisions à propos de rapports d'enquête administrative</li>
                    <li>Renseignements détaillés sur les plans de continuité des activités</li>
                </ul>
                <h4><span class="wb-inv">Sécurité </span>Protégé C :</h4>
                <ul>
                    <li>Renseignements détaillés concernant des enquêtes sur des menaces pour des personnes</li>
                    <li>Noms d'informateurs de la police et renseignements détaillés à leur sujet</li>
                    <li>Renseignements détenus dans le cadre du Programme de protection des témoins</li>
                    <li>Renseignements commerciaux fournis par une tierce partie</li>
                </ul>
            </details>
        </li>
    </ul>
</div>
<p>Si vous avez des exemples spécifiques que vous voudriez voir inclus dans cet outil concernant votre domaine d'expertise, veuillez-nous faire parvenir vos commentaires et recommandations à&nbsp;: <a href="mailto:nc-csop-smop-gd@hrsdc-rhdcc.gc.ca?subject=Outil%20de%20catégorisation%20de%20l'information" class="text-nowrap">nc-csop-smop-gd@hrsdc-rhdcc.gc.ca</a></p>

<!-- 
OUTIL D'ÉVALUATION DE PRÉJUDICE
-->
<section class="panel panel-primary">
    <header class="panel-heading">
        <h2 id="prejudice" class="panel-title">Outil d'évaluation de préjudice</h2>
    </header>
    <div class="panel-body">
        <div class="alert alert-warning">
            <h3>Déterminer le niveau de sécurité de votre information en utilisant l'outil d'évaluation de préjudice</h3>
        </div>
        <p>Si vous ne parvenez pas à identifier la catégorie de vos informations d'après les définitions et les exemples fournis dans les sections précédentes de cette page, vous pouvez utiliser l'outil d'évaluation des préjudices pour déterminer le niveau de sécurité. Cet outil vous aidera à évaluer le préjudice que l'on peut raisonnablement s'attendre à subir en cas de compromission. Pour déterminer le degré de préjudice, on tient compte de la <strong>gravité</strong>, c'est‑à‑dire le niveau de dommages (par exemple entre une blessure et un décès) et de la <strong>portée</strong> (nombre de personnes, d'organisations, d'installations ou de systèmes touchés, ou étendue de la région géographique concernée par exemple selon que le préjudice est localisé ou répandu), ou encore selon la durée du préjudice (court ou long terme, etc.).</p>
        <p><a href="/fra/si/securite/categorisation/form-outil-cat-info.shtml" class="btn btn-success h5">Procéder à l'outil d'évaluation de préjudice</a></p>
        <h3>Pourquoi la catégorisation appropriée est-elle importante ?</h3>
        <p>La sur-catégorisation et la sous-catégorisation des informations présentent un risque pour la sécurité.</p>
        <p>La sur-catégorisation impose des restrictions et des niveaux de protection plus élevés qui empêchent les informations d'arriver là où elles doivent être. Cela crée également des charges et des coûts inutiles si la catégorisation n'est pas appropriée. Par exemple, le traitement numérique d'informations classifiées nécessite :</p>
        <ul>
            <li>Le déploiement de systèmes de communication coûteux, comme l'Infrastructure secrète du gouvernement du Canada;</li>
            <li>La mise en place de zones sécurisées et hautement sécurisées ; et,</li>
            <li>Des mesures de sécurité plus strictes liées à sa manipulation, son stockage, sa distribution et sa destruction tout au long de son cycle de vie.</li>
        </ul>
        <p class="mrgn-tp-md">La sous-catégorisation des informations signifie que les mesures de sécurité appropriées ne sont pas appliquées, ce qui crée un risque élevé de compromission, entra&icirc;nant un incident de sécurité impliquant une divulgation, un retrait, une modification ou une destruction non- autorisé.</p>
        <p>Dès le départ, il incombe au propriétaire, à l'auteur ou au rédacteur de l'information d'attribuer le bon niveau de sensibilité (classifié ou protégé). L'attribution d'une catégorie de sensibilité aux informations (par exemple, Secret, Protégé B) vous oblige à évaluer le niveau de préjudice et d'impact qui se produirait si l'information était compromise. Pour éviter la sur-catégorisation et la sous-catégorisation des informations, il est essentiel d'évaluer avec précision le niveau de préjudice.</p>
        <p>Lors de l'évaluation de la valeur et du niveau de préjudice potentiel des informations, assurez-vous d'inclure le point de vue de toutes les parties prenantes de l'information ou des biens. Si l'on évaluait ensemble plusieurs cas d'informations sensibles, le préjudice causé par toutes les informations combinées pourrait être plus élevé que si des informations individuelles étaient compromises seules.</p>
    </div>
</section>
</main>

<nav class="wb-sec col-md-3 col-md-pull-9" typeof="SiteNavigationElement" id="wb-sec" role="navigation">
    <h2 id="wb-sec-h" class="wb-inv">Menu de la section</h2>
    <section class="list-group menu list-unstyled" id="left_nav">
        <tvar data-tvar="left_nav"><div data-ajax-append="/_conf/assets/fr/nav_gauche/si/si_securite_gauche.html" class="original"></tvar>
    </section>
</nav>
</div> <!-- div row -->
</div> <!-- div container -->
