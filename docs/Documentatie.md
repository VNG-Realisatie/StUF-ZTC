---
layout: page-with-side-nav
title: Documentatie StUF-ZTC
folder_files:
  - title: Ztc0310 20260227 patch34.zip (zip)
    path: documenten/ztc0310_20250825_patch33.zip
    group: 310
    versie: 34
    status: Definitief
    omschrijving: Patch naar aanleiding van de wijziging van de maximale lengte van de landnaam van 40 posities naar 80 posities in de LO-BRP.  
	Daarnaast zijn ook enkele verbeteringen in de documentatie aangebracht. Bevat alle documentatie, schema's en WSDL's behorende bij patch 34 van StUF-BG 3.10, StUF-ZKN 3.10 en StUF-ZTC 3.10 inclusief alle bij de StUF 3.01 onderlaag horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-BG 3.10, StUF-ZKN 3.10 en StUF-ZTC 3.10 horende extraElementen.
    datum: 20260227
  - title: Verstuffing ZTC (pdf)
    path: documenten/Verstuffing_ZTC.pdf
    group: 310
    versie: 13-1-2026 
    status: Definitief
    omschrijving: 
    datum: 20160113
  - title: Extra-elementen voor ztc0310 (zip)
    path: documenten/Extra-elementen_voor_ztc0310.zip
    group: 310
    versie: 15-1-2026
    status: Definitief
    omschrijving: Bevat alle extraElementen t/m patch 34.
    datum: 20260115
---

# Documentatie

## StUF-ZTC 3.10

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 310 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

