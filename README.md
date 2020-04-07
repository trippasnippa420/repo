# repo<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<addons>
<addon id="plugin.video.addon6q"
       name="[COLOR gray][B]Addon[COLOR yellow]6q[/COLOR][/B][/COLOR]"
       version="1.0.0"
       provider-name="6q">

  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.2.1"/>
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.beautifulsoup4" />
    <import addon="script.module.simple.downloader" version="0.9.4"/>
    <import addon="script.module.requests" />
    <import addon="script.module.httplib2" />
    <import addon="script.module.youtube.dl" />
    <import addon="plugin.video.youtube" />
    <import addon="script.module.urlresolver" />
    <import addon="script.module.simplejson" />
  </requires>
  <extension point="xbmc.python.pluginsource" library="default.py">
    <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>addon 6q</summary>
    <description>
         Add-on exclusivo y gratuito, si lo ves an algún otro lugar... ya sabes... infórmame.


    </description>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.f4mTester" version="2.6.2" name="f4mTester" provider-name="Shani">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
        <import addon="script.video.F4mProxy" version="2.6.2"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="default.py">
        <provides>video</provides>
    </extension>
    <extension point="xbmc.addon.metadata">
        <summary>f4mTester</summary>
        <description></description>
        <platform>all</platform>
    </extension>
</addon>

<addon id="plugin.video.p2p-streams"
       name="p2p-streams"
       version="1.2.0b"
       provider-name="enen92,fightnight">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.beautifulsoup" version="3.0.8"/>
    <import addon="script.module.simplejson" />
    <import addon="script.module.pytz" />
    <import addon="script.module.requests" />
    <import addon="script.module.mechanize" version="0.2.6"/>
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides>video</provides>
  </extension>
  <extension point="xbmc.addon.metadata">
    <summary>SopCast and AceStream</summary>
    <description lang="en">AceStream and Sopcast in your favourite media center! Watch peer-to-peer streams in Kodi without the need for external players. Project page: https://github.com/enen92/P2P-Streams-Kodi</description>
    <description lang="pt">AceStream e Sopcast no seu Media-Center de eleição! Assista a streams peer-to-peer no Kodi sem a necessidade de players externos. Página do projecto: https://github.com/enen92/P2P-Streams-Kodi</description>
    <description lang="nl">Acestream en Sopcast in jouw favoriete media center. Kijk peer-to-peer streams in Kodi zonder de noodzaak voor externe spelers. Project pagina: https://github.com/enen92/P2P-Streams-Kodi/</description>
    <description lang="it">AceStream e SopCast nel tuo Media Center preferito! Guarda i canali peer-to-peer in Kodi senza la necessità di player esterni. Pagina del progetto: https://github.com/enen92/P2P-Streams-Kodi/</description>
    <disclaimer lang="en">The authors does not host nor distribute any of the content you may watch using this addon. The authors have no affiliation with any of the content providers. This addon does not track its users.</disclaimer>
    <disclaimer lang="pt">Os autores não alojam nem distribuem nenhum do conteúdo acessível a partir deste addon. Os autores não têm qualquer afiliação com nenhum dos sites utilizados por este addon. O addon não contem nenhuma ferramenta de tracking.</disclaimer>
    <disclaimer lang="nl">De auteurs houden of delen niets van de inhoud die u kunt bekijken met behulp van deze addon. De auteurs hebben geen banden met welke leverancier van inhoud dan ook. Deze addon houdt geen gegevens bij van zijn gebruikers.</disclaimer>
    <disclaimer lang="it">L'autore non detiene o distribuisce alcun contenuto fruibile tramite l'utilizzo di questo addon. L'autore non è affiliato con nessun fornitore dei contenuti. Questo addon non traccia i suoi utenti.</disclaimer>
    <forum>http://forum.kodi.tv/showthread.php?tid=201894</forum>
    <source>https://github.com/enen92/P2P-Streams-Kodi | https://github.com/enen92/P2P-Streams-Kodi--Modules-</source>
    <website>https://code.google.com/p/p2p-strm/</website>
    <platform>all</platform>
  </extension>
</addon>

<addon id="plugin.video.pulsar" name="Pulsar" version="0.7.1" provider-name="steeve, i96751414">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="navigation.py">
        <provides>video</provides>
    </extension>
    <extension point="xbmc.service" library="service.py" start="startup"/>
    <extension point="xbmc.python.module" library="resources/site-packages" />
    <extension point="xbmc.subtitle.module" library="navigation.py" />
    <extension point="xbmc.addon.metadata">
        <platform>all</platform>
        <language>en</language>
        <website><![CDATA[https://github.com/i96751414/plugin.video.pulsar]]></website>
        <forum><![CDATA[http://forum.xbmc.org/showthread.php?tid=200957]]></forum>
        <source><![CDATA[https://github.com/i96751414/plugin.video.pulsar]]></source>
        <language>en</language>
        <license><![CDATA[Non commercial. See https://github.com/i96751414/plugin.video.pulsar/blob/master/LICENSE]]></license>
        <summary><![CDATA[Pulsar: Universal streaming]]></summary>
        <description><![CDATA[Follow @pulsarhq on Twitter]]> PS: If you install Pulsar not you must have installed Quasar on Kodi / PD: Si instala Pulsar no debe tener instalado Quasar en Kodi</description>
    </extension>
</addon>

<addon id="plugin.video.quasar" name="Quasar" version="0.9.35" provider-name="scakemyer">
    <requires>
        <import addon="xbmc.python" version="2.1.0"/>
    </requires>
    <extension point="xbmc.python.pluginsource" library="navigation.py">
        <provides>video</provides>
    </extension>
    <extension point="xbmc.service" library="service.py" start="startup"/>
    <extension point="xbmc.python.module" library="resources/site-packages" />
    <extension point="xbmc.subtitle.module" library="navigation.py" />
    <extension point="xbmc.addon.metadata">
        <platform>all</platform>
        <language>en</language>
        <website><![CDATA[https://github.com/scakemyer/plugin.video.quasar]]></website>
        <forum><![CDATA[http://forum.kodi.tv/showthread.php?tid=257967]]></forum>
        <source><![CDATA[https://github.com/scakemyer/plugin.video.quasar]]></source>
        <language>en</language>
        <license><![CDATA[Non commercial. See https://github.com/scakemyer/plugin.video.quasar/blob/master/LICENSE]]></license>
        <summary><![CDATA[Quasar: Torrent streaming]]></summary>
        <description><![CDATA[Stream torrent files]]></description>
    </extension>
</addon>

<addon id="plugin.video.ZemTV-shani"
       name="Zem"
       version="5.7.3"
       provider-name="shani">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
	<import addon="script.module.urlresolver" version="1.0.0"/>
	<import addon="plugin.video.youtube" version="2.9.2" optional="true"/>
    <import addon="script.module.simplejson" version="3.3.0"/>
       	<import addon="script.module.elementtree" version="1.2.8"/>


    <import addon="plugin.video.f4mTester" version="2.2.3" optional="true" />

  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides>video</provides>
  </extension>

   <extension point="xbmc.addon.repository" name="shani repository">
        <info compressed="false">https://offshoregit.com/Shani-08/main/addons.xml</info>
        <checksum>https://offshoregit.com/Shani-08/main/addons.xml.md5</checksum>
        <datadir zip="true">https://offshoregit.com/Shani-08/main/zips/</datadir>
    </extension>




  <extension point="xbmc.addon.metadata">
    <summary>Zem Addon for sports and desi contents. Visit TVADDONS.ag for support</summary>
    <description>Watch Sports and Desi contents on your XBMC. This plugin fetches the video sources from various platforms and locations</description>
    <disclaimer lang="en">The author does not host or distribute any of the content displayed by this addon. The author does not have any affiliation with any of the content provider.</disclaimer>
    <forum>https://forums.tvaddons.ag/shanis-addon-repository/</forum>
    <email>@shani_08_kodi</email>
    <platform>all</platform>


  </extension>
</addon>

<addon id="program.plexus"
       name="Plexus"
       version="0.1.4"
       provider-name="enen92, TV ADDONS">
  <requires>
    <import addon="xbmc.python" version="2.1.0"/>
    <import addon="script.module.requests" />
  </requires>
  <extension point="xbmc.python.pluginsource"
            library="default.py">
        <provides>executable</provides>
  </extension>

  <extension point="xbmc.addon.metadata">
    <summary>SopCast and AceStream for Kodi</summary>
    <description lang="en">Plexus - Any complex structure containing an intricate network of parts. Plexus brings native peer-to-peer support (AceStream and SopCast) for Kodi Entertainment Center for several platforms.[CR][CR]Documentation: (missing)</description>
    <description lang="pt">Plexus - Uma estrutura complexa constituída por uma rede de partes. O Plexus adiciona suporte peer-to-peer nativo (AceStream e Sopcast) ao Kodi Entertainment Center para várias plataformas.[CR][CR]Documentação: (em falta)</description>
    <disclaimer lang="en">The author does not host nor distribute any of the content you may watch using this addon. The author has no part in the development of any included technologies. When seeking help in Kodi's forum please respect rules (http://kodi.wiki/view/Forum_rules).</disclaimer>
    <disclaimer lang="pt">Os autores não alojam nem distribuem nenhum do conteúdo que poderá ser reproduzido a partir deste addon. Os autores não têm qualquer parte no desenvolvimento de qualquer uma das tecnologias. Se procurar ajuda no fórum oficial do Kodi por favor respeite as regras do fórum (http://kodi.wiki/view/Forum_rules).</disclaimer>
    <forum>http://forums.tvaddons.ag</forum>
    <platform>all</platform>
  </extension>
</addon>

<addon id="repository.kodi-addon6q" name="addon6q Official Repo" version="1.0.0" provider-name="addon6q">
	<extension point="xbmc.addon.repository" name="addon6q official Repo">
		<info compressed="false">https://raw.githubusercontent.com/siskolopez/repoaddon6q/master/addons.xml</info>
		<checksum>https://raw.githubusercontent.com/siskolopez/repoaddon6q/master/addons.xml.md5</checksum>
                <datadir zip="true">https://raw.githubusercontent.com/siskolopez/repoaddon6q/master</datadir>
	</extension>
	<extension point="xbmc.addon.metadata">
		<summary>addon6q Official Repository</summary>
                <description lang="en">Install Addon Official addon6q and other add-ons that are complementary help in support links</description>
   		<description lang="es">Instala el Addon Oficial addon6q y los otros add-ons que son complementos de ayuda en la reproduccion de las listas</description>
		<disclaimer></disclaimer>
		<platform>all</platform>
	</extension>
</addon>
</addons>
