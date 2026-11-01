---
layout: home
lang: en
permalink: /en/
title: HARMONY
description: Website of the HARMONY research project
---

<section class="background-light pad" id="info">
    <div class="container text-justify">
        <p class="section-eyebrow">The research project</p>
        <h2>Physics and data. Advancing together.</h2>
        <div class="row">
            <div class="col-lg-12 col-md-12">
                <p class="text-justify">
                The HARMONY project aims to develop interpretable, robust and real-time-capable hybrid process models for the vacuum recirculation (RH) process in steel production—a key technology in the transition to sustainable and resource-efficient metallurgy. By integrating symbolic (physics-based) and subsymbolic (data-driven) AI into a hybrid modelling approach, the project enables the extraction of unmeasurable process parameters, improves process understanding and supports operational optimisation. {{ site.data.i18n.t.footer.fundingtext[page.lang] }} <a target="_blank" href="{{ site.data.i18n.t.footer.ffg-link[page.lang] }}">https://www.ffg.at/ai-tech-green-2025</a>.
                </p>
                <h3>A shared data foundation</h3>
                <p class="text-justify">
                The project combines domain-specific knowledge management, advanced sensor systems and data preprocessing to create a unified, high-quality data pool. This provides the foundation for modular, easily adaptable hybrid models that can support future industrial control applications. Particular emphasis is placed on model robustness, including tolerance to noisy or incomplete data and generalisability across different operating conditions.
                </p>
                <h3>Models that incorporate knowledge</h3>
                <p class="text-justify">
                A methodological innovation of the project is the application and further development of knowledge-driven symbolic regression. By incorporating structural building blocks, symbolic models—such as physical laws and domain-specific equations—can be integrated directly into the otherwise subsymbolic, data-driven modelling process. This approach enables hybrid models that are not only accurate but also physically consistent and interpretable.
                </p>
                <h3>For industrial practice</h3>
                <p class="text-justify">
                The project places great emphasis on collaboration between humans and AI to ensure that the models remain understandable and usable for non-experts and can be adapted to changing plant conditions. This supports their long-term use and the responsible application of AI in industry.
                </p>
                <p class="text-justify">
                Validation case studies, sustainability assessments and evaluations of industrial applicability in controlled environments will demonstrate the impact of the developed models.
                </p>
                <h3>Project objectives</h3>
                <p>
                HARMONY aims to develop hybrid process models for a vacuum recirculation process that will become a key process in the transition to sustainable steel production routes.

                The hybrid models are intended to:
                </p>
                <ul>
                <li>integrate domain-specific knowledge with symbolic and subsymbolic modelling techniques,</li>
                <li>enable the extraction of unmeasurable, process-relevant parameters,</li>
                <li>contribute to a deeper understanding of complex metallurgical processes,</li>
                <li>provide improved process models with higher predictive accuracy,</li>
                <li>support resource-efficient process optimisation and thereby contribute to SDG 9 and SDG 12.</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<section class="background-light pad" id="team">
    <div class="container text-justify">
        <p class="section-eyebrow">Our consortium</p>
        <h2>Research thrives on collaboration.</h2>

        <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12">
                <p>
                Developing innovative methods and concepts in hybrid modelling and their application to the RH process requires collaboration across research disciplines. The success of this project therefore depends on an interdisciplinary team that brings together complementary expertise. HARMONY involves researchers from <i>K1-MET GmbH, FH OÖ F&E GmbH, research group HEAL,</i> and <i>voestalpine Stahl GmbH</i>.
                </p>
            </div>
        </div>

        <div class="row image-row">
            <div class="col-lg-4 col-md-12 text-center topic-box">
                <a target="_blank" href="{{ site.data.i18n.t.footer.k1met-link[page.lang] }}">
                <figure class="image-box"><img id="image-k1metlogo" src="/{{ site.data.assets.image-k1metlogo }}" alt="K1-MET" /></figure>
                </a>
            </div>
            <div class="col-lg-4 col-md-12 text-center topic-box">            
                <a target="_blank" href="{{ site.data.i18n.t.footer.heal-link[page.lang] }}">
                <figure class="image-box"><img id="image-heallogo" src="/{{ site.data.assets.image-heallogo }}" alt="FH OÖ – HEAL" /></figure>
                </a>
            </div>
            <div class="col-lg-4 col-md-12 text-center topic-box">
                <a target="_blank" href="{{ site.data.i18n.t.footer.vas-link[page.lang] }}">
                <figure class="image-box"><img id="image-vaslogo" src="/{{ site.data.assets.image-vaslogo }}" alt="voestalpine" /></figure>
                </a>
            </div>
        </div>

        <div class="row contact-info">
            <div class="col-lg-4 col-md-12">
                <h4>Magdalena Schatzl</h4>
                <table class="contact-table">
                    <tr><td>Role:</td><td>Project management</td></tr>
                    <tr><td>Phone:</td><td>+43 50804 27114</td></tr>                  
                    <tr><td>Mail:</td><td><a href="mailto:magdalena.schatzl@k1-met.com">magdalena.schatzl[at]k1-met.com</a></td></tr>
                </table>
            </div>
            <div class="col-lg-4 col-md-12">
                <h4>Jan Zenisek</h4>
                <table class="contact-table">
                    <tr><td>Role:</td><td>FH OÖ coordination</td></tr>
                    <tr><td>Phone:</td><td>+43 50804 27114</td></tr>                  
                    <tr><td>Mail:</td><td><a href="mailto:magdalena.schatzl@k1-met.com">magdalena.schatzl[at]k1-met.com</a></td></tr>
                </table>
            </div>
            <div class="col-lg-4 col-md-12">
                <h4>Roman Rössler</h4>
                <table class="contact-table">
                    <tr><td>Role:</td><td>voestalpine coordination</td></tr>
                    <tr><td>Phone:</td><td>+43 50804 27114</td></tr>                  
                    <tr><td>Mail:</td><td><a href="mailto:magdalena.schatzl@k1-met.com">magdalena.schatzl[at]k1-met.com</a></td></tr>
                </table>
            </div>
        </div>
    </div>
</section>


{% include map.html %}
