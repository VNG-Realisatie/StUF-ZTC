---
layout: page-with-side-nav
title: Documentatie StUF-ZTC
folder_files:
  - title: Extra-elementen voor ztc0310.xls
    path: documenten/Extra-elementen_voor_ztc0310.zip
    group: 310
    versie: 3-12-2021
    status: Definitief
    omschrijving: 
    datum: 20211208
  - title: Verstuffing ZTC
    path: documenten/Verstuffing_ZTC.pdf
    group: 310
    versie: 
    status: Definitief
    omschrijving: 
    datum: 20140611
  - title: Ztc0310 20211208 patch32
    path: documenten/Ztc0310_20211208_patch32.zip
    group: 310
    versie: 32
    status: Definitief
    omschrijving: Bevat alle documentatie, schema's en WSDL's behorende bij patch 32 van StUF-ZTC 3.10 inclusief alle bij de StUF 3.01 onderlaag en StUF-BG 3.10 horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken.
    datum: 20211208
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

