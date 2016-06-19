---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#

layout: page
#   header: 
#    image_fullwidth: header_unsplash_12.jpg

header:
    image: zrzut1.png
#    title: - Analiza danych NGS
    background-color: "#fabb00"

# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

widget1:
  title: "Blog & Portfolio"
#  url: 'http://phlow.github.io/feeling-responsive/blog/'
#  image: widget-1-302x182.jpg
  text: 'Every good portfolio website has a blog with fresh news, thoughts and develop&shy;ments of your activities. <em>Feeling Responsive</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'
widget2:
  title: "Why use this theme?"
#  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href="http://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
#  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
#  url: 'https://github.com/Phlow/feeling-responsive'
#  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'

callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert

permalink: /index.html

#
---

Cześć !

Nazywam się Paweł Kamiński i od 8-miu lat zajmuję się analizą danych biologicznych. Początkowo były to analizy danych mikromacierzowych, a obecnie przede wszystkim dane pochodzące z sekwencjonowanie NGS.
Aktualnie kończę przygotowywać doktorat z zakresu bioinformatyki.

Oferuję analizy danych NGS odpłatne, bądź w zamian za umieszczenie nazwiska w publikacji. Warunki do uzgodnienia.
Służę również pomocą w zakresie przygotowania eksperymentu do sekwencjonowania NGS: ilośc powtórzeń biologicznych, głębokość sekwencjonowania, itp.

Do analizy najchętniej przyjmuję dane w postaci surowej, w formacie FASTQ, ale nie stanowi dla mnie problemu przeprowadzenie analizy w oparciu o dane w innym formacie (np. BAM czy SAM, lub vcf). Dysponując danymi w postaci surowej mogę przeprowadzić analizę jakości samego procesu sekwencjonowania NGS i odfiltrować odczyty o złej jakości. Po takim etapie analizy jakościowej w zależności od postawionego celu badania zazwyczaj przeprowadza się mapowanie do genomu referencyjnego. Najczęściej spotykaną sytuacją jest analiza transkryptomu, RNA-seq, i określenie genów, które zmieniły swą ekspresję w reakcji na określony czynnik - diferential gene expression. Zestawiająć otrzymaną w analizie listę genów, których ekspresja się zmieniła, z danymi zawartymi w Gene Ontology, bądź w podobnych źródłach, można stwierdzić których szlaków metabolicznych (pathway analysis/enrichment) te zmiany dotyczą.

Opisana powyżej analiza transkryptomu, choć spotykana najczęściej, nie jest jedyną możliwą do przeprowadzenia. Oferuję pełen zakres analiz i stale czekam na nowe, nawet te trudne i złożone wyzwania. Sekwencjonowanie NGS w szczególności pozwala:

### &lt;ul&
- określić występujący wariant genu (SNP)
- na analizę copy number variation
- odkrycie nowego miRNA
- określenie miejsc wiązania miRNA

