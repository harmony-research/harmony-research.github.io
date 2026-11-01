---
layout: home
lang: de
permalink: /
title: HARMONY
description: Website des Forschungsprojekts HARMONY
---

<section class="background-light pad" id="info">
    <div class="container text-justify">
        <p class="section-eyebrow">Das Forschungsprojekt</p>
        <h2>Physik und Daten. Gemeinsam weiter.</h2>
        <div class="row">
            <div class="col-lg-12 col-md-12">
                <p class="text-justify">
                    Das Projekt HARMONY verfolgt das Ziel, interpretierbare, robuste und echtzeitfähige hybride Prozessmodelle für den Vakuumrezirkulationsprozess (RH) in der Stahlproduktion zu entwickeln – eine Schlüsseltechnologie im Übergang zu einer nachhaltigen und ressourceneffizienten Metallurgie. Durch die Integration von symbolischer (physikbasierter) und subsymbolischer (datengetriebener) KI in einen hybriden Modellierungsansatz ermöglicht das Projekt die Extraktion nicht messbarer Prozessparameter, verbessert das Prozessverständnis und unterstützt die operative Optimierung. {{ site.data.i18n.t.footer.fundingtext[page.lang] }} <a target="_blank" href="{{ site.data.i18n.t.footer.ffg-link[page.lang] }}">https://www.ffg.at/ai-tech-green-2025</a>.
                </p>
                <h3>Eine gemeinsame Datengrundlage</h3>
                <p class="text-justify">
                Das Projekt kombiniert domänenspezifisches Wissensmanagement, fortschrittliche Sensorsysteme und Datenvorverarbeitung, um einen einheitlichen, qualitativ hochwertigen Datenpool zu schaffen. Diese Grundlage dient der Entwicklung modularer, leicht neu adaptierbarer, hybrider Modelle, die für zukünftige industrielle Steuerungs- oder Regelungsanwendungen von Nutzen sind. Ein besonderer Fokus liegt auf der Robustheit der Modelle, einschließlich ihrer Toleranz gegenüber verrauschten oder unvollständigen Daten sowie ihrer Generalisierbarkeit über verschiedene Betriebsbedingungen hinweg.
                </p>
                <h3>Modelle, die Wissen einbeziehen</h3>
                <p class="text-justify">
                Eine methodische Innovation des Projekts ist die Anwendung und Weiterentwicklung wissensgetriebener symbolischer Regression. Durch die Einbindung sogenannter struktureller Bausteine können symbolische Modelle – wie physikalische Gesetze und domänenspezifische Gleichungen – direkt in den ansonsten subsymbolischen, also datengetriebenen Modellierungsprozess integriert werden. Dieser Ansatz ermöglicht die Erstellung hybrider Modelle, die nicht nur genau, sondern auch physikalisch konsistent und interpretierbar sind.
                </p>
                <h3>Für die industrielle Praxis</h3>
                <p class="text-justify">
                Das Projekt legt großen Wert auf die Zusammenarbeit zwischen Mensch und KI, um sicherzustellen, dass die Modelle für Nicht-Expert:innen verständlich und nutzbar bleiben sowie an sich verändernde Anlagenbedingungen angepasst werden können – und damit eine langfristige Nutzbarkeit und verantwortungsvolle KI-Anwendung in der Industrie unterstützen.
                </p>
                <p class="text-justify">
                Validierungs-Fallstudien, Nachhaltigkeitsbewertungen und Evaluierungen der industriellen Anwendbarkeit in kontrollierten Umgebungen werden die Wirkung der entwickelten Modelle demonstrieren. 
                </p>
                <h3>Projektziele</h3>
                <p>
                HARMONY zielt darauf ab, hybride Prozessmodelle für einen Vakuum-Umwälzprozess zu entwickeln, der im Zuge der Transformation hin zu nachhaltigen Stahlproduktionsrouten zu einem Schlüsselprozess werden wird.

                Die hybriden Modelle sollen:</p>
                <ul>
                <li>domänenspezifisches Wissen mit symbolischen und subsymbolischen Modellierungstechniken integrieren,</li>
                <li>die Extraktion nicht messbarer, prozessrelevanter Parameter ermöglichen,</li>
                <li>zu einem tieferen Verständnis komplexer metallurgischer Prozesse beitragen,</li>
                <li>verbesserte Prozessmodelle mit höherer Vorhersagegenauigkeit liefern,</li>
                <li>eine ressourceneffiziente Prozessoptimierung unterstützen und damit zu SDG 9 und SDG 12 beitragen.</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<section class="background-dark pad" id="blog">
    <div class="container">
        <p class="section-eyebrow">Aktuelles aus der Forschung</p>
        <h2>Einblicke ins Projekt</h2>
        {% if site.posts.size > 0 %}
        <div class="row">
            <div class="col-lg-12 col-md-12">
                {% for post in site.posts limit:1 %}
                    {% include post_preview.html preview_size_small=true %}
                {% endfor %}
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12 text-right">
                <a href="/blog" id="btn-blog" class="btn btn-xl btn-slim-primary blog-button">Mehr Posts</a>
            </div>
        </div>
        {% else %}
        <div class="row"><div class="col-lg-12"><h4>Sorry, there are currently no posts available.</h4></div></div>
        {% endif %}
    </div>
</section>

<section class="background-light pad" id="team">
    <div class="container text-justify">
        <p class="section-eyebrow">Unser Konsortium</p>
        <h2>Forschung braucht Zusammenarbeit.</h2>

        <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12">
                <p>Die Entwicklung innovativer Methoden und Konzepte im Forschungsfeld Hybride Modellierung und dem Anwendungsgebiet RH-Prozess verlangt nach der Synthese von Forschungsdisziplinen. Ein Schlüssel zum Erfolg dieses Forschungsprojekts liegt daher in der Zusammenarbeit eines interdispziplinären Teams, das verschiedene Kompetenzen einbringt und zusammenführt. Am Projekt HARMONY sind Forscher*innen der Organisationen <i>K1-MET GmbH, FH OÖ F&E GmbH Forschungsgruppe HEAL,</i> und <i>voestalpine Stahl GmbH</i> beteiligt.</p>
            </div>
        </div>

        <div class="row image-row">
            <div class="col-lg-4 col-md-12 text-center topic-box">
                <a target="_blank" href="{{ site.data.i18n.t.links.k1met[page.lang] }}">
                <figure class="image-box"><img id="image-k1metlogo" src="/{{ site.data.assets.image-k1metlogo }}" alt="K1-MET" /></figure>
                </a>
            </div>
            <div class="col-lg-4 col-md-12 text-center topic-box">            
                <a target="_blank" href="{{ site.data.i18n.t.links.heal[page.lang] }}">
                <figure class="image-box"><img id="image-heallogo" src="/{{ site.data.assets.image-heallogo }}" alt="FH OÖ – HEAL" /></figure>
                </a>
            </div>
            <div class="col-lg-4 col-md-12 text-center topic-box">
                <a target="_blank" href="{{ site.data.i18n.t.links.vas[page.lang] }}">
                <figure class="image-box"><img id="image-vaslogo" src="/{{ site.data.assets.image-vaslogo }}" alt="voestalpine" /></figure>
                </a>
            </div>
        </div>

        <div class="row contact-info">
            <div class="col-lg-4 col-md-12">
                <h4>Magdalena Schatzl</h4>
                <table class="contact-table">
                    <tr><td>Funktion:</td><td>Projektleitung</td></tr>
                    <tr><td>Tel.:</td><td>+43 50804 27114</td></tr>                  
                    <tr><td>Mail:</td><td><a href="mailto:magdalena.schatzl@k1-met.com">magdalena.schatzl[at]k1-met.com</a></td></tr>
                </table>
            </div>
            <div class="col-lg-4 col-md-12">
                <h4>Jan Zenisek</h4>
                <table class="contact-table">
                    <tr><td>Funktion:</td><td>Koordination FH OÖ</td></tr>
                    <tr><td>Tel.:</td><td>+43 50804 27114</td></tr>                  
                    <tr><td>Mail:</td><td><a href="mailto:magdalena.schatzl@k1-met.com">magdalena.schatzl[at]k1-met.com</a></td></tr>
                </table>
            </div>
            <div class="col-lg-4 col-md-12">
                <h4>Roman Rössler</h4>
                <table class="contact-table">
                    <tr><td>Funktion:</td><td>Koordination voestalpine</td></tr>
                    <tr><td>Tel.:</td><td>+43 50804 27114</td></tr>                  
                    <tr><td>Mail:</td><td><a href="mailto:magdalena.schatzl@k1-met.com">magdalena.schatzl[at]k1-met.com</a></td></tr>
                </table>
            </div>
        </div>
    </div>
</section>


{% include map.html %}
