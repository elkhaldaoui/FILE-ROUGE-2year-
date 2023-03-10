<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>ARRIVA STORE</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="e9b7a808-3d8f-4d29-b535-0f72cba2ee44" class="page sans"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1556740714-a8395b3bf30f?ixlib=rb-4.0.3&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><img class="icon" src="https://www.notion.so/icons/shop_pink.svg"/></div><h1 class="page-title">ARRIVA STORE</h1></header><div class="page-body"><hr id="f1140cf2-d4a8-4e9e-9a35-ae07e0d904ef"/><h1 id="aac6c154-5b7d-473e-964c-7f9763055cb9" class=""><code><strong><strong>CONTEXTE DU PROJET</strong></strong></code></h1><pre id="8ed77c2d-6477-4ea3-9629-efc22eb0ef8d" class="code code-wrap"><code>ARRIVA STORE est une application web e-commerce qui utilise la pile technologique MERN (MongoDB, ExpressJS, ReactJS et NodeJS) pour fournir une plateforme de vente en ligne intuitive, rapide et sécurisée. L&#x27;application offre aux utilisateurs la possibilité de parcourir une large sélection de produits, d&#x27;ajouter des articles à leur panier, de passer des commandes et de suivre l&#x27;état de leur livraison.
L&#x27;objectif principal de l&#x27;application est de permettre aux utilisateurs de parcourir les produits disponibles à la vente, d&#x27;ajouter des produits à leur panier d&#x27;achat, de passer des commandes, de suivre leurs commandes et de fournir des commentaires et des évaluations des produits achetés.

La pile MERN est une combinaison de technologies modernes, open-source et largement utilisées qui permettent aux développeurs de créer des applications web hautement évolutives et réactives. MongoDB est une base de données NoSQL qui permet de stocker des données non structurées et semi-structurées. ExpressJS est un framework web qui facilite la création d&#x27;applications web avec NodeJS. ReactJS est une bibliothèque JavaScript pour la création d&#x27;interfaces utilisateur dynamiques et réactives, tandis que NodeJS est un environnement d&#x27;exécution JavaScript côté serveur.

L&#x27;application ARRIVA STORE est conçue pour offrir une expérience utilisateur fluide et agréable. Elle est dotée d&#x27;une interface utilisateur moderne et conviviale, d&#x27;une fonctionnalité de recherche avancée, d&#x27;un système de paiement sécurisé et d&#x27;un système de gestion de commande. En outre, l&#x27;application est entièrement personnalisable et extensible, ce qui permet aux développeurs de l&#x27;adapter à leurs besoins spécifiques.

En somme, ARRIVA STORE est une application web e-commerce puissante et flexible qui offre une expérience d&#x27;achat en ligne fluide et sécurisée. Elle est soutenue par une pile technologique robuste et moderne qui permet aux développeurs de créer des applications web hautement évolutives et réactives.</code></pre><h1 id="96356cae-8283-4a39-a273-409a0a713f01" class=""><code><strong>HISTOIRES D&#x27;UTILISATEURS</strong></code></h1><ul id="5e9ad0b9-a839-4112-9b08-4709236c9c55" class="toggle"><li><details open=""><summary><strong><mark class="highlight-red">En tant qu&#x27;administrateur</mark></strong></summary><p id="6d39491a-26e8-4abe-a8c5-08d865752295" class="">Ajouter des nouvelles catégories ou bien modifier les paramétrages de l’application.</p></details></li></ul><ul id="01168208-edda-464b-ac7d-3049840d2a04" class="toggle"><li><details open=""><summary><mark class="highlight-blue"><strong>En tant qu&#x27;utilisateur </strong></mark></summary><blockquote id="b4ccb7da-18f9-48d9-8ecd-e7e5399ecb3f" class="">Tout le monde peut postuler des articles dans ARRIVA STORE.<ul id="7dff919e-884c-455c-9b91-2a17eef6ae6c" class="bulleted-list"><li style="list-style-type:disc">La possibilité de rechercher des produits par mot-clé, catégorie, prix et autres filtres pertinents.</li></ul><ul id="62b57641-1f1c-4421-a1ce-45991b290e9f" class="bulleted-list"><li style="list-style-type:disc">La possibilité de visualiser les produits sous différents angles avec des images de haute qualité et des descriptions détaillées.</li></ul><ul id="c5f51542-1d09-49ec-b215-9a1477d7e9c6" class="bulleted-list"><li style="list-style-type:disc">La possibilité de créer un compte utilisateur et de se connecter avec des identifiants personnels.</li></ul><ul id="6614dba3-26cf-4831-ac25-52d339d41f20" class="bulleted-list"><li style="list-style-type:disc">La possibilité d&#x27;ajouter des produits au panier d&#x27;achat et de gérer les articles ajoutés.</li></ul><ul id="e5e0f0d9-dd4a-4d2a-a6e3-1a0334175ce9" class="bulleted-list"><li style="list-style-type:disc">La possibilité de passer des commandes, de fournir une adresse de livraison et de suivre l&#x27;état de la commande en temps réel.</li></ul><ul id="d248a141-cdff-45cc-a364-cf0968156264" class="bulleted-list"><li style="list-style-type:disc">La possibilité de laisser des commentaires et des évaluations des produits achetés.</li></ul><ul id="9f7f63b6-f266-42f7-825d-573db64b6e71" class="bulleted-list"><li style="list-style-type:disc">La possibilité d&#x27;envoyer des notifications par e-mail aux utilisateurs sur les mises à jour de commande, les promotions ou les nouvelles offres de produits.</li></ul></blockquote><ul id="42745f34-8e83-4177-a5d8-d24c94a85acf" class="toggle"><li><details open=""><summary><code><strong>Les critères d&#x27;acceptation :</strong></code></summary><ul id="5e0ea3cd-486e-4e9c-a06e-e71b06931740" class="bulleted-list"><li style="list-style-type:disc">Un formulaire d&#x27;inscription pour chauffeur est disponible sur site web.</li></ul><ul id="af46f017-de02-4465-a642-4cd97f7cc110" class="bulleted-list"><li style="list-style-type:disc">Les champs requis pour devenir un utilisateur sont :<ol type="1" id="4efb8e7a-cf6f-4f00-9b5b-2f2738356ffe" class="numbered-list" start="1"><li>Prénom de l’utilisateur.</li></ol><ol type="1" id="5779d55e-0992-42a0-b5cd-f45a7938918c" class="numbered-list" start="2"><li>Nom de l’utilisateur.</li></ol><ol type="1" id="685e617b-4e06-4107-9c16-4f559bf74134" class="numbered-list" start="3"><li>Email de l’utilisateur.</li></ol><ol type="1" id="278e3c74-4b68-423e-ad24-67de417ebfff" class="numbered-list" start="4"><li>CIN de l’utilisateur.</li></ol><ol type="1" id="e8f0c5a3-2fcc-46ce-9f55-59311af16d55" class="numbered-list" start="5"><li>Votre Numéro de Téléphone.</li></ol></li></ul><ul id="f5c25340-e742-41ff-90db-804f52edbccf" class="bulleted-list"><li style="list-style-type:disc">Il peut recevoir les commandes directement du client sur l&#x27;application</li></ul></details></li></ul></details></li></ul><hr id="eb07c5dc-5e6f-4bbe-877a-d73a99e11460"/><p id="592d7a48-66c7-42fd-9287-ae0a9b11fdcd" class="">
</p><h1 id="3b3b6a20-6f21-4ab4-bbbf-a4a5a858b1da" class=""><code><strong>EXIGENCES TECHNOLOGIQUES</strong></code></h1><ul id="d7adef59-84f7-41b1-90bd-93d9ad9e9399" class="toggle"><li><details open=""><summary><strong>Front-End :</strong></summary><ul id="e9536a58-5380-4027-8d09-41664ad60aa8" class="bulleted-list"><li style="list-style-type:disc">ReactJS </li></ul><ul id="177bbb10-c7d7-442d-83ff-aee8e9a33a98" class="bulleted-list"><li style="list-style-type:disc">BOOTSTRAP5 </li></ul><ul id="4275401b-7494-47d8-8eb5-75f81d9982f4" class="bulleted-list"><li style="list-style-type:disc">HTML5 </li></ul><ul id="b73383a9-3e96-4b57-906e-7488b82836dc" class="bulleted-list"><li style="list-style-type:disc">CSS3</li></ul></details></li></ul><ul id="5ba868a6-7b2c-4e85-9327-28c27f686a4c" class="toggle"><li><details open=""><summary><strong>Back-End :</strong></summary><ul id="83e58abf-fe0d-4100-b219-594b9bbffb69" class="bulleted-list"><li style="list-style-type:disc">Node JS / Express JS</li></ul><ul id="d834ad0d-e233-493c-b94b-6696a5e11869" class="bulleted-list"><li style="list-style-type:disc">JWT (<strong>Authentification</strong>)</li></ul><ul id="ba0fef3a-e8f0-442b-b3ef-a82115c518ac" class="bulleted-list"><li style="list-style-type:disc">Mongoose</li></ul></details></li></ul><ul id="12e97621-52ba-42c5-9ab8-06414ca88d5e" class="toggle"><li><details open=""><summary><strong>Database :</strong></summary><ul id="8e489732-cc78-41c3-b331-98622c0dda53" class="bulleted-list"><li style="list-style-type:disc">MongoDB</li></ul></details></li></ul><ul id="47fa3bdc-a94c-4f14-82f1-66d00e8e89e2" class="toggle"><li><details open=""><summary><strong>Tools :</strong></summary><ul id="01c6addf-db0c-4cb7-a4cf-29489048a93a" class="bulleted-list"><li style="list-style-type:disc">Docker (Containers)</li></ul><ul id="5f1a5317-dbec-4e8d-a905-d538848779da" class="bulleted-list"><li style="list-style-type:disc">Jest (Test Unitaire)</li></ul></details></li></ul><ul id="87168117-1742-4c85-a8f3-88ae4116b9ab" class="toggle"><li><details open=""><summary><strong>Mobile :</strong></summary><p id="23d1867b-c09e-4c2d-8715-30ab67cde760" class="">Responsive application</p></details></li></ul><hr id="07842371-72fe-4ac8-a665-74f176cc5be8"/></div></article></body></html>
