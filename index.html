import { createFileRoute } from "@tanstack/react-router";
import { useEffect, useMemo, useState } from "react";

export const Route = createFileRoute("/")({
  component: ArabWorldApp,
});

// ---------- DATA (identical content, minor factual fixes on tag/hobby) ----------

type Country = { key: string; flag: string; name: string };
const countries: Country[] = [
  { key: "algerien", flag: "🇩🇿", name: "Algerien" },
  { key: "bahrain", flag: "🇧🇭", name: "Bahrain" },
  { key: "komoren", flag: "🇰🇲", name: "Komoren" },
  { key: "dschibuti", flag: "🇩🇯", name: "Dschibuti" },
  { key: "aegypten", flag: "🇪🇬", name: "Ägypten" },
  { key: "irak", flag: "🇮🇶", name: "Irak" },
  { key: "jordanien", flag: "🇯🇴", name: "Jordanien" },
  { key: "kuwait", flag: "🇰🇼", name: "Kuwait" },
  { key: "libanon", flag: "🇱🇧", name: "Libanon" },
  { key: "libyen", flag: "🇱🇾", name: "Libyen" },
  { key: "mauretanien", flag: "🇲🇷", name: "Mauretanien" },
  { key: "marokko", flag: "🇲🇦", name: "Marokko" },
  { key: "oman", flag: "🇴🇲", name: "Oman" },
  { key: "palaestina", flag: "🇵🇸", name: "Palästina" },
  { key: "katar", flag: "🇶🇦", name: "Katar" },
  { key: "saudi", flag: "🇸🇦", name: "Saudi-Arabien" },
  { key: "somalia", flag: "🇸🇴", name: "Somalia" },
  { key: "sudan", flag: "🇸🇩", name: "Sudan" },
  { key: "syrien", flag: "🇸🇾", name: "Syrien" },
  { key: "tunesien", flag: "🇹🇳", name: "Tunesien" },
  { key: "vae", flag: "🇦🇪", name: "Vereinigte Arabische Emirate" },
  { key: "jemen", flag: "🇾🇪", name: "Jemen" },
];

type Loc = { key: "stadt" | "land"; icon: string; label: string; sub: string };
const locations: Record<string, Loc[]> = {
  algerien: [{ key: "stadt", icon: "🏙️", label: "Algier", sub: "Hauptstadt am Mittelmeer" }, { key: "land", icon: "🏜️", label: "Sahara", sub: "Wüste & Oasen" }],
  bahrain: [{ key: "stadt", icon: "🏙️", label: "Manama", sub: "Inselhauptstadt" }, { key: "land", icon: "🦪", label: "Küstendorf", sub: "Perlentaucher-Tradition" }],
  komoren: [{ key: "stadt", icon: "🏙️", label: "Moroni", sub: "Hauptstadt auf Grande Comore" }, { key: "land", icon: "🌋", label: "Vulkandorf", sub: "Am Fuß des Karthala" }],
  dschibuti: [{ key: "stadt", icon: "🏙️", label: "Dschibuti-Stadt", sub: "Hafenstadt am Roten Meer" }, { key: "land", icon: "🏜️", label: "Afar-Region", sub: "Nomadenland" }],
  aegypten: [{ key: "stadt", icon: "🏙️", label: "Kairo", sub: "Großstadt am Nil" }, { key: "land", icon: "🌾", label: "Dorf am Nil", sub: "Landwirtschaft" }],
  irak: [{ key: "stadt", icon: "🏙️", label: "Bagdad", sub: "Hauptstadt am Tigris" }, { key: "land", icon: "🌾", label: "Marschland", sub: "Zwischen Euphrat & Tigris" }],
  jordanien: [{ key: "stadt", icon: "🏙️", label: "Amman", sub: "Hauptstadt" }, { key: "land", icon: "🏜️", label: "Nähe Petra", sub: "Wüstenstadt-Region" }],
  kuwait: [{ key: "stadt", icon: "🏙️", label: "Kuwait-Stadt", sub: "Ölmetropole am Golf" }, { key: "land", icon: "🏜️", label: "Wüste", sub: "Beduinen-Tradition" }],
  libanon: [{ key: "stadt", icon: "🏙️", label: "Beirut", sub: "Hauptstadt am Meer" }, { key: "land", icon: "⛰️", label: "Zedern-Gebirge", sub: "Bergdorf" }],
  libyen: [{ key: "stadt", icon: "🏙️", label: "Tripolis", sub: "Hauptstadt am Mittelmeer" }, { key: "land", icon: "🏜️", label: "Ghadames", sub: "Oasenstadt am Wüstenrand" }],
  mauretanien: [{ key: "stadt", icon: "🏙️", label: "Nouakchott", sub: "Hauptstadt am Atlantik" }, { key: "land", icon: "🐫", label: "Sahara", sub: "Nomadenfamilien" }],
  marokko: [{ key: "stadt", icon: "🏙️", label: "Marrakesch", sub: "Souks & Medina" }, { key: "land", icon: "⛰️", label: "Atlas-Gebirge", sub: "Berberdorf" }],
  oman: [{ key: "stadt", icon: "🏙️", label: "Maskat", sub: "Hauptstadt am Golf von Oman" }, { key: "land", icon: "🏔️", label: "Bergdorf", sub: "Terrassenfelder im Hadschar" }],
  palaestina: [{ key: "stadt", icon: "🏙️", label: "Ramallah", sub: "Stadt im Westjordanland" }, { key: "land", icon: "🫒", label: "Dorf", sub: "Olivenanbau" }],
  katar: [{ key: "stadt", icon: "🏙️", label: "Doha", sub: "Moderne Hauptstadt" }, { key: "land", icon: "🏜️", label: "Wüste", sub: "Beduinen-Erbe" }],
  saudi: [{ key: "stadt", icon: "🏙️", label: "Riad", sub: "Moderne Großstadt" }, { key: "land", icon: "🏜️", label: "Wüste", sub: "Beduinen-Gemeinschaft" }],
  somalia: [{ key: "stadt", icon: "🏙️", label: "Mogadischu", sub: "Hauptstadt am Indischen Ozean" }, { key: "land", icon: "🐪", label: "Nomadenland", sub: "Kamelhirten" }],
  sudan: [{ key: "stadt", icon: "🏙️", label: "Khartum", sub: "Am Zusammenfluss beider Nile" }, { key: "land", icon: "🌾", label: "Dorf am Nil", sub: "Landwirtschaft" }],
  syrien: [{ key: "stadt", icon: "🏙️", label: "Damaskus", sub: "Eine der ältesten Städte der Welt" }, { key: "land", icon: "🌾", label: "Dorf", sub: "Landwirtschaft im Umland" }],
  tunesien: [{ key: "stadt", icon: "🏙️", label: "Tunis", sub: "Hauptstadt am Mittelmeer" }, { key: "land", icon: "🏜️", label: "Tozeur", sub: "Oasenstadt am Sahara-Rand" }],
  vae: [{ key: "stadt", icon: "🏙️", label: "Dubai", sub: "Wolkenkratzer-Stadt" }, { key: "land", icon: "🏖️", label: "Küstendorf", sub: "Fischerei & Perlentauchen" }],
  jemen: [{ key: "stadt", icon: "🏙️", label: "Sanaa", sub: "Hauptstadt im Hochland" }, { key: "land", icon: "🏔️", label: "Bergdorf", sub: "Terrassenfelder" }],
};

const baseStories: Record<string, string> = {
  algerien_stadt_wohlhabend: "Du lebst mit deiner Familie in einer eleganten Wohnung mit Blick auf die Bucht von Algier, ein Fahrer bringt dich morgens zur zweisprachigen Privatschule.",
  algerien_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in der Altstadt (Kasbah) von Algier, du gehst zu Fuß mit Freunden zur Schule, während deine Eltern in Büro und Geschäft arbeiten.",
  algerien_stadt_einfach: "Deine Familie lebt in einem einfachen Haus am Stadtrand von Algier, der Schulweg führt mit einem vollen Bus quer durch die Stadt, danach hilfst du am Marktstand deiner Mutter.",
  algerien_land_wohlhabend: "Deine Familie besitzt eine große Dattelpalmen-Oase am Rand der Sahara und ein komfortables Haus, ein Fahrer bringt dich zur Schule in der nächsten Oasenstadt.",
  algerien_land_mittelschicht: "Deine Familie bewirtschaftet einen kleinen Dattelgarten in einer Sahara-Oase, du gehst mit deinen Geschwistern zur Dorfschule und hilfst am Nachmittag bei der Bewässerung.",
  algerien_land_einfach: "Schon früh hilfst du, Wasser aus dem Brunnen der Oase zu schöpfen, der Schulweg führt über heißen Sand, oft mehr als eine Stunde zu Fuß.",
  bahrain_stadt_wohlhabend: "Deine Familie lebt in einer Luxuswohnung in Manama mit Blick auf den Golf, ein Fahrer bringt dich zur internationalen Schule, am Wochenende segelst du mit deinem Vater.",
  bahrain_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Manama, du fährst mit dem Schulbus zur staatlichen Schule, während deine Eltern im Bankwesen oder im Handel arbeiten.",
  bahrain_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Manamas, zur Schule fährst du mit einem vollen Bus, danach hilfst du in der kleinen Werkstatt deines Onkels.",
  bahrain_land_wohlhabend: "Deine Familie besitzt ein Boot für Perlentaucher-Touren und ein schönes Haus am Meer, du wirst in die Stadt zur Schule gefahren.",
  bahrain_land_mittelschicht: "Deine Familie betreibt ein kleines Fischerboot in einem Küstendorf Bahrains, du gehst zu Fuß mit Freunden zur Schule und hilfst nachmittags beim Sortieren des Fangs.",
  bahrain_land_einfach: "Schon früh hilfst du deinem Vater, die Fischernetze vorzubereiten, bevor du den Weg zur Dorfschule läufst, wo früher viele Familien vom Perlentauchen lebten.",
  komoren_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus mit Vanille- und Gewürzplantagen nahe Moroni, ein Fahrer bringt dich zur Schule in der Hauptstadt.",
  komoren_stadt_mittelschicht: "Deine Familie lebt in einem soliden Haus in Moroni, du gehst zu Fuß mit Freunden zur Schule, dein Vater arbeitet im Hafen, deine Mutter verkauft Gewürze auf dem Markt.",
  komoren_stadt_einfach: "Deine Familie lebt in einem einfachen Haus am Rand von Moroni, der Schulweg führt über staubige Straßen, danach hilfst du beim Sortieren von Vanilleschoten für den Verkauf.",
  komoren_land_wohlhabend: "Deine Familie besitzt Land am Fuß des Vulkans Karthala mit Ylang-Ylang-Plantagen und lebt in einem komfortablen Haus, du wirst zur Schule gefahren.",
  komoren_land_mittelschicht: "Deine Familie bewirtschaftet ein kleines Feld am Vulkanhang, du gehst mit deinen Geschwistern zur Dorfschule und hilfst beim Ernten von Kokosnüssen.",
  komoren_land_einfach: "Schon früh hilfst du, Feuerholz zu sammeln und Wasser zu holen, der Schulweg führt über vulkanisches Gestein, oft barfuß.",
  dschibuti_stadt_wohlhabend: "Deine Familie lebt in einem klimatisierten Haus in Dschibuti-Stadt, ein Fahrer bringt dich zur internationalen Schule, dein Vater arbeitet im großen Hafen.",
  dschibuti_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Dschibuti-Stadt, du gehst zu Fuß zur Schule, deine Eltern arbeiten im Handel und in der Verwaltung.",
  dschibuti_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel der Hauptstadt, zur Schule fährst du mit einem vollen Bus, danach hilfst du am kleinen Marktstand deiner Familie.",
  dschibuti_land_wohlhabend: "Deine Familie besitzt eine große Kamelherde und ein festes Haus am Rand der Afar-Region, du wirst zur nächsten Schule gefahren.",
  dschibuti_land_mittelschicht: "Deine Familie hält Kamele und Ziegen und lebt in einem einfachen, aber festen Haus, ein Schulbus holt dich an einem Sammelpunkt in der Wüste ab.",
  dschibuti_land_einfach: "Schon im Morgengrauen hilfst du, die Kamele zur Weide zu treiben, danach läufst du weit durch die heiße Ebene, um die Schule zu erreichen.",
  aegypten_stadt_wohlhabend: "Du lebst mit deiner Familie in einer modernen Hochhauswohnung im Neubauviertel New Cairo, weit weg vom Trubel der Altstadt. Ein Fahrer bringt dich jeden Morgen zu deiner zweisprachigen Privatschule, während zu Hause eine Haushälterin kocht und putzt.",
  aegypten_stadt_mittelschicht: "Deine Familie lebt in einer gemütlichen Wohnung nahe einem belebten Markt in Kairo. Du gehst mit Nachbarskindern zu Fuß zur staatlichen Schule, während deine Eltern beide berufstätig sind.",
  aegypten_stadt_einfach: "Deine Familie wohnt in einem einfachen Haus in einem dicht besiedelten Viertel Kairos. Der Schulweg dauert mit einem überfüllten Minibus fast eine Stunde, danach hilfst du oft am Straßenstand deines Vaters, der Koshari verkauft.",
  aegypten_land_wohlhabend: "Deine Familie besitzt große Felder am Nilufer und ein schönes Haus mit Garten voller Mangobäume. Ein Fahrer bringt dich zur Schule in der nächsten Stadt, während die meisten anderen Dorfkinder den langen Weg zu Fuß gehen.",
  aegypten_land_mittelschicht: "Deine Familie bewirtschaftet ein solides Stück Land am Nil und lebt in einem gemauerten Haus mit Blick auf die Felder. Du gehst mit deinen Geschwistern zur Dorfschule und hilfst danach bei der Ernte von Baumwolle oder Mais.",
  aegypten_land_einfach: "Noch vor Sonnenaufgang hilfst du deiner Familie, Wasser vom Nil zu holen und die Ziegen zu füttern. Der Schulweg führt fast eine Stunde über staubige Feldwege, danach hilfst du beim Ernten auf dem Feld eines Nachbarn.",
  irak_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus in einem ruhigen Viertel Bagdads, ein Fahrer bringt dich zur Privatschule, am Nachmittag hast du Musikunterricht.",
  irak_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Bagdad nahe dem Tigris, du gehst mit Freunden zur Schule, dein Vater arbeitet als Ingenieur.",
  irak_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Bagdads, der Schulweg führt durch enge Gassen, danach hilfst du am Obst- und Gemüsestand deiner Familie.",
  irak_land_wohlhabend: "Deine Familie besitzt fruchtbares Ackerland zwischen Euphrat und Tigris und ein solides Haus, du wirst zur Schule in die nächste Stadt gefahren.",
  irak_land_mittelschicht: "Deine Familie bewirtschaftet ein Stück Land im Marschland des Zweistromlands, du fährst mit einem traditionellen Schilfboot zur Dorfschule.",
  irak_land_einfach: "Schon früh hilfst du beim Fischen und Sammeln von Schilf im Marschland, der Schulweg führt über schmale Wasserwege mit dem Boot.",
  jordanien_stadt_wohlhabend: "Deine Familie lebt in einem modernen Haus in West-Amman mit Garten und Poolzugang. Ein Fahrer bringt dich zu deiner Privatschule, am Nachmittag hast du Klavier- oder Sprachunterricht.",
  jordanien_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Amman. Du gehst mit deinen Geschwistern zur staatlichen Schule, während dein Vater als Lehrer und deine Mutter im Krankenhaus arbeitet.",
  jordanien_stadt_einfach: "Deine Familie lebt in einem einfachen Haus in der Altstadt von Amman. Zur Schule fährst du in einem geteilten Sammeltaxi, danach hilfst du in der kleinen Bäckerei deiner Familie.",
  jordanien_land_wohlhabend: "Deine Familie besitzt ein Reiseunternehmen mit Kamelen und Pferden für Touristen nahe der antiken Stadt Petra und lebt in einem komfortablen Haus. Du wirst in die nächste Stadt zur Schule gefahren, statt wie viele andere zu Fuß zu gehen.",
  jordanien_land_mittelschicht: "Deine Familie betreibt einen kleinen Souvenirladen nahe den Ruinen von Petra und lebt in einem soliden Haus aus Sandstein. Du gehst mit Freunden zur Dorfschule und hilfst am Nachmittag im Laden.",
  jordanien_land_einfach: "Schon vor der Schule hilfst du, Touristen auf Eseln durch die engen Schluchten von Petra zu begleiten. Danach läufst du einen langen Weg durch die Wüstenlandschaft zur Schule.",
  kuwait_stadt_wohlhabend: "Deine Familie lebt in einer Villa in Kuwait-Stadt, ein Fahrer bringt dich zur internationalen Schule, am Wochenende hast du Reitunterricht.",
  kuwait_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Kuwait-Stadt, du fährst mit dem Schulbus zur Schule, dein Vater arbeitet in der Ölindustrie.",
  kuwait_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel, zur Schule fährst du mit einem vollen Bus, danach hilfst du im kleinen Laden deines Onkels.",
  kuwait_land_wohlhabend: "Deine Familie besitzt ein großes Wüstencamp mit Geländewagen und Falken und ein Haus in der Stadt, du wirst weit zur Schule gefahren.",
  kuwait_land_mittelschicht: "Deine Familie hält Kamele und verbringt Wochenenden im Beduinen-Zelt in der Wüste, du besuchst eine Schule in der nächsten Kleinstadt.",
  kuwait_land_einfach: "Schon früh hilfst du, die Kamele deiner Familie zu versorgen, der Schulweg führt weit durch den Sand bis zur Hauptstraße.",
  libanon_stadt_wohlhabend: "Deine Familie lebt in einer Wohnung mit Meerblick in Beirut. Ein Fahrer bringt dich zu deiner zweisprachigen Privatschule, am Nachmittag hast du Segel- oder Musikunterricht.",
  libanon_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in einem lebendigen Viertel Beiruts. Du gehst zu Fuß mit Freunden zur Schule, während deine Eltern beide berufstätig sind.",
  libanon_stadt_einfach: "Deine Familie lebt in einer kleinen Wohnung in Beirut. Zur Schule fährst du in einem geteilten Sammeltaxi (Service), danach hilfst du am Manakish-Stand deiner Familie.",
  libanon_land_wohlhabend: "Deine Familie besitzt ein Weingut mit Blick auf die berühmten Zedernwälder im Libanongebirge und lebt in einem großen Steinhaus. Du wirst ins Tal zur Schule gefahren, während andere Dorfkinder den steilen Weg zu Fuß nehmen.",
  libanon_land_mittelschicht: "Deine Familie bewirtschaftet einen kleinen Apfel- und Kirschgarten im Gebirge und lebt in einem soliden Steinhaus. Du gehst mit deinen Geschwistern zur Dorfschule, oft durch dichten Nebel im Winter.",
  libanon_land_einfach: "Früh am Morgen hilfst du bei der Obsternte in den Terrassenfeldern des Gebirges. Der Schulweg führt über eine steile Bergstraße, die im Winter manchmal sogar verschneit ist.",
  libyen_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus in Tripolis mit Blick aufs Mittelmeer, ein Fahrer bringt dich zur Privatschule.",
  libyen_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Tripolis, du gehst mit Freunden zur Schule, deine Eltern arbeiten im Handel.",
  libyen_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel von Tripolis, der Schulweg führt durch enge Gassen der Altstadt, danach hilfst du am Marktstand.",
  libyen_land_wohlhabend: "Deine Familie besitzt Palmenhaine in der Oasenstadt Ghadames und ein traditionelles Lehmhaus, du wirst zur Schule in die nächste Stadt gefahren.",
  libyen_land_mittelschicht: "Deine Familie bewirtschaftet einen Dattelgarten am Rand der Oase, du gehst mit deinen Geschwistern zur Dorfschule.",
  libyen_land_einfach: "Schon früh hilfst du bei der Bewässerung der Palmen, der Schulweg führt über heißen Wüstensand, oft mehr als eine Stunde.",
  mauretanien_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus in Nouakchott nahe dem Atlantik, ein Fahrer bringt dich zur Privatschule.",
  mauretanien_stadt_mittelschicht: "Deine Familie lebt in einem Haus in Nouakchott, du gehst zu Fuß zur Schule, dein Vater fährt mit dem berühmten Eisenerzzug zur Arbeit.",
  mauretanien_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Nouakchotts, der Schulweg führt über sandige Straßen, danach hilfst du am Fischmarkt am Hafen.",
  mauretanien_land_wohlhabend: "Deine Familie besitzt eine große Kamelherde und mehrere Geländewagen und lebt komfortabel am Rand der Sahara, du wirst weit zur Schule gefahren.",
  mauretanien_land_mittelschicht: "Deine Familie zieht mit einer kleinen Kamelherde durch die Sahara und schlägt zeitweise ein Zeltlager auf, ein Wanderlehrer unterrichtet euch mehrmals pro Woche.",
  mauretanien_land_einfach: "Schon im Morgengrauen hilfst du, die Kamele zu melken und Wasser zu finden, eine feste Schule gibt es selten, gelernt wird oft unterwegs.",
  marokko_stadt_wohlhabend: "Du wohnst mit deiner Familie in einem prächtigen Riad mit Innenhof, Springbrunnen und Orangenbäumen mitten in der Medina von Marrakesch. Ein Fahrer bringt dich zu deiner zweisprachigen Privatschule, am Nachmittag lernst du Reiten in einem privaten Club.",
  marokko_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung nahe dem großen Souk von Marrakesch. Du gehst zu Fuß mit Freunden zur staatlichen Schule, dein Vater betreibt eine kleine Werkstatt für Lederwaren im Souk.",
  marokko_stadt_einfach: "Deine Familie lebt in einem einfachen Haus am Rand der Medina. Nach der Schule hilfst du deinem Vater beim Färben von Leder in den berühmten Gerbereien, wo es streng, aber auch faszinierend riecht.",
  marokko_land_wohlhabend: "Deine Familie besitzt ein großes Anwesen mit Olivenhainen und einer Argan-Ölproduktion am Fuß des Atlas-Gebirges. Du wirst jeden Morgen ins Tal zur Schule gefahren, während viele andere Kinder den steilen Bergpfad zu Fuß nehmen.",
  marokko_land_mittelschicht: "Deine Familie hütet eine kleine Herde Ziegen und besitzt ein solides Steinhaus mit Blick auf die schneebedeckten Gipfel. Du gehst mit deinen Geschwistern zur Dorfschule, an manchen Tagen über eine Stunde zu Fuß.",
  marokko_land_einfach: "Schon vor der Schule hilfst du, die Ziegen auf die Weide zu treiben und Wasser von der Quelle zu holen. Der Schulweg führt über einen steinigen Bergpfad, oft in Sandalen, egal ob es regnet oder die Sonne brennt.",
  oman_stadt_wohlhabend: "Deine Familie lebt in einem Haus mit Meerblick in Maskat, ein Fahrer bringt dich zur internationalen Schule, am Wochenende tauchst du in klarem Wasser.",
  oman_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Maskat, du gehst zu Fuß zur Schule, dein Vater arbeitet im Hafen.",
  oman_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Maskats, der Schulweg führt an der Küste entlang, danach hilfst du am Fischstand deiner Familie.",
  oman_land_wohlhabend: "Deine Familie besitzt Terrassenfelder mit Granatapfel- und Rosenanbau im Hadschar-Gebirge und ein schönes Haus, du wirst ins Tal zur Schule gefahren.",
  oman_land_mittelschicht: "Deine Familie bewirtschaftet Terrassenfelder in den Bergen und lebt in einem soliden Steinhaus, du gehst mit deinen Geschwistern zur Dorfschule.",
  oman_land_einfach: "Schon früh hilfst du beim Bewässern der Terrassenfelder über das alte Falaj-Kanalsystem, der Schulweg führt steil bergab und wieder bergauf.",
  palaestina_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus in Ramallah, ein Fahrer bringt dich zur zweisprachigen Privatschule, am Nachmittag hast du Musikunterricht.",
  palaestina_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Ramallah, du gehst mit Freunden zu Fuß zur Schule, deine Eltern arbeiten im Büro und als Lehrerin.",
  palaestina_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel, der Schulweg führt über steile Gassen, danach hilfst du in der kleinen Bäckerei deiner Familie.",
  palaestina_land_wohlhabend: "Deine Familie besitzt große Olivenhaine am Rand des Dorfes und ein komfortables Steinhaus, du wirst zur Schule in die nächste Stadt gefahren.",
  palaestina_land_mittelschicht: "Deine Familie bewirtschaftet einen Olivenhain und lebt in einem soliden Haus, jeden Herbst hilft die ganze Familie bei der Olivenernte.",
  palaestina_land_einfach: "Schon früh hilfst du bei der Olivenernte auf den Feldern der Familie, der Schulweg führt über steinige Pfade zwischen den Terrassen.",
  katar_stadt_wohlhabend: "Deine Familie lebt in einer Villa in Doha mit Blick auf die Skyline, ein Fahrer bringt dich zur internationalen Schule, am Wochenende reitest du Falken vor.",
  katar_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Doha, du fährst mit dem Schulbus, dein Vater arbeitet in der Gasindustrie.",
  katar_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Dohas, zur Schule fährst du mit einem vollen Bus, danach hilfst du im Laden deines Onkels.",
  katar_land_wohlhabend: "Deine Familie besitzt ein großes Wüstencamp mit Kamelen für Rennen und ein Haus in der Stadt, du wirst weit zur Schule gefahren.",
  katar_land_mittelschicht: "Deine Familie hält Kamele und verbringt viele Wochenenden in der Wüste, du besuchst eine Schule in der nächsten Kleinstadt.",
  katar_land_einfach: "Schon früh hilfst du, die Kamele deiner Familie zu versorgen, der Schulweg führt weit durch den Sand.",
  saudi_stadt_wohlhabend: "Deine Familie lebt in einer Villa mit Pool in einem gesicherten Wohnkomplex in Riad. Ein Fahrer bringt dich zu deiner internationalen Schule, am Wochenende hast du Falknerei- oder Reitunterricht.",
  saudi_stadt_mittelschicht: "Deine Familie lebt in einer geräumigen Wohnung in Riad. Du fährst mit einem Fahrgemeinschafts-Auto zur Schule, während dein Vater im Büro und deine Mutter als Ärztin arbeitet.",
  saudi_stadt_einfach: "Deine Familie lebt in einem einfachen Haus am Stadtrand von Riad. Zur Schule fährst du mit einem vollen Bus, danach hilfst du oft im kleinen Lebensmittelladen deines Onkels.",
  saudi_land_wohlhabend: "Deine Familie besitzt eine große Kamelherde und mehrere Geländewagen und lebt in einem komfortablen Haus am Rand der Wüste. Du wirst weit in die nächste Stadt zur Schule gefahren.",
  saudi_land_mittelschicht: "Deine Familie züchtet Kamele und Ziegen und lebt in einem festen Haus, das im Sommer für ein paar Wochen gegen ein traditionelles Beduinenzelt getauscht wird. Ein Schulbus holt dich morgens an einem Sammelpunkt in der Wüste ab.",
  saudi_land_einfach: "Schon im Morgengrauen hilfst du, die Kamele und Ziegen zur Weide zu treiben. Danach läufst du ein gutes Stück durch den Sand, um den Schulbus an der Hauptstraße zu erreichen.",
  somalia_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus in Mogadischu nahe dem Meer, ein Fahrer bringt dich zur Privatschule.",
  somalia_stadt_mittelschicht: "Deine Familie lebt in einem Haus in Mogadischu, du gehst zu Fuß zur Schule, dein Vater arbeitet im Hafen, deine Mutter im Handel.",
  somalia_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Mogadischus, der Schulweg führt über staubige Straßen, danach hilfst du am Marktstand deiner Familie.",
  somalia_land_wohlhabend: "Deine Familie besitzt eine große Kamel- und Ziegenherde und ein festes Haus, du wirst zur Schule in die nächste Stadt gefahren.",
  somalia_land_mittelschicht: "Deine Familie zieht mit einer mittelgroßen Herde durch das Weideland, ein Wanderlehrer unterrichtet dich mehrmals pro Woche unter einem großen Baum.",
  somalia_land_einfach: "Schon im Morgengrauen hilfst du, die Herde zu den Wasserstellen zu treiben, eine feste Schule gibt es selten, gelernt wird oft von den Ältesten.",
  sudan_stadt_wohlhabend: "Deine Familie lebt in einem großen Haus in Khartum, dort wo sich der Weiße und der Blaue Nil vereinen, ein Fahrer bringt dich zur Privatschule.",
  sudan_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Khartum, du gehst zu Fuß zur Schule, deine Eltern arbeiten im Büro und auf dem Markt.",
  sudan_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Khartums, der Schulweg führt über staubige Straßen, danach hilfst du am Teestand deiner Mutter.",
  sudan_land_wohlhabend: "Deine Familie besitzt große Felder am Nilufer und ein solides Haus, du wirst zur Schule in die nächste Stadt gefahren.",
  sudan_land_mittelschicht: "Deine Familie bewirtschaftet ein Stück Land am Nil und lebt in einem gemauerten Haus, du gehst mit deinen Geschwistern zur Dorfschule.",
  sudan_land_einfach: "Schon früh hilfst du, Wasser vom Nil zu holen und die Felder zu bewässern, der Schulweg führt über staubige Pfade.",
  syrien_stadt_wohlhabend: "Deine Familie lebt in einem schönen Haus mit Innenhof in der Altstadt von Damaskus, einer der ältesten durchgehend bewohnten Städte der Welt, ein Fahrer bringt dich zur Schule.",
  syrien_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Damaskus, du gehst mit Freunden zu Fuß zur Schule, dein Vater arbeitet im großen Souk.",
  syrien_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel von Damaskus, der Schulweg führt über enge Gassen, danach hilfst du am kleinen Stand deiner Familie.",
  syrien_land_wohlhabend: "Deine Familie besitzt Obstgärten im fruchtbaren Umland von Damaskus und ein solides Haus, du wirst zur Schule gefahren.",
  syrien_land_mittelschicht: "Deine Familie bewirtschaftet einen kleinen Obst- und Olivengarten und lebt in einem soliden Haus, du gehst mit deinen Geschwistern zur Dorfschule.",
  syrien_land_einfach: "Schon früh hilfst du bei der Ernte von Aprikosen oder Oliven auf dem Feld der Familie, der Schulweg führt über staubige Landstraßen.",
  tunesien_stadt_wohlhabend: "Deine Familie lebt in einem eleganten Haus im Vorort La Marsa nahe Tunis, ein Fahrer bringt dich zur zweisprachigen Privatschule.",
  tunesien_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Tunis, du gehst zu Fuß zur Schule, deine Eltern arbeiten im Büro und im Textilhandel.",
  tunesien_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel von Tunis, der Schulweg führt durch enge Gassen der Medina, danach hilfst du am Marktstand deiner Familie.",
  tunesien_land_wohlhabend: "Deine Familie besitzt eine große Dattelpalmen-Oase in Tozeur am Rand der Sahara und ein komfortables Haus, du wirst zur Schule gefahren.",
  tunesien_land_mittelschicht: "Deine Familie bewirtschaftet einen Dattelgarten in der Oase Tozeur, du gehst mit deinen Geschwistern zur Dorfschule.",
  tunesien_land_einfach: "Schon früh hilfst du bei der Bewässerung der Palmen in der Oase, der Schulweg führt über heißen Sand bis zur nächsten Schule.",
  vae_stadt_wohlhabend: "Deine Familie lebt in einer Luxuswohnung mit Blick auf den Burj Khalifa. Ein privater Fahrer bringt dich zur internationalen Schule, am Wochenende hast du Tennis- oder Segelunterricht.",
  vae_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in einem belebten Viertel Dubais. Ein Schulbus holt dich morgens ab, während deine Eltern im Handel oder in einem Büro arbeiten.",
  vae_stadt_einfach: "Deine Familie lebt in einer einfachen Wohnung in einem Arbeiterviertel am Stadtrand von Dubai. Zur Schule fährst du mit einem vollen Bus, danach hilfst du manchmal am Marktstand deiner Familie.",
  vae_land_wohlhabend: "Deine Familie besitzt mehrere Boote für Tauch- und Angeltouren mit Touristen und lebt in einem großen Haus nahe dem Strand. Du wirst zur Schule in die nächste Stadt gefahren und lernst am Wochenende von erfahrenen Perlentauchern.",
  vae_land_mittelschicht: "Deine Familie betreibt ein kleines Fischerboot und lebt in einem soliden Haus nahe dem Hafen. Du gehst zu Fuß mit Freunden zur Schule und hilfst nachmittags beim Sortieren des Fangs.",
  vae_land_einfach: "Schon früh am Morgen hilfst du deinem Vater, die Fischernetze für den Tag vorzubereiten. Danach legst du den langen Schulweg im warmen Sand zurück.",
  jemen_stadt_wohlhabend: "Deine Familie lebt in einem traditionellen Turmhaus aus Lehm im historischen Zentrum von Sanaa, ein Fahrer bringt dich zur Privatschule.",
  jemen_stadt_mittelschicht: "Deine Familie lebt in einer Wohnung in Sanaa, du gehst zu Fuß zur Schule, dein Vater arbeitet im großen Souk der Altstadt.",
  jemen_stadt_einfach: "Deine Familie lebt in einem einfachen Viertel Sanaas, der Schulweg führt über steile Gassen, danach hilfst du am Stand deiner Familie.",
  jemen_land_wohlhabend: "Deine Familie besitzt weitläufige Terrassenfelder mit Kaffeeanbau im Hochland und ein solides Steinhaus, du wirst zur Schule gefahren.",
  jemen_land_mittelschicht: "Deine Familie bewirtschaftet Terrassenfelder in den Bergen und lebt in einem einfachen Steinhaus, du gehst mit deinen Geschwistern zur Dorfschule.",
  jemen_land_einfach: "Schon früh hilfst du beim Bewässern der steilen Terrassenfelder, der Schulweg führt über schmale Bergpfade, oft mehr als eine Stunde.",
};

// Regional pause snacks per country to fix "everyone eats Manakish" issue
const tagStorySchultagByLand: Record<string, string> = {
  algerien: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Baguette mit Käse oder ein Karantita, während ihr über die Hausaufgaben lästert.",
  bahrain: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du in der Schulkantine einen Sambosa oder ein Käsesandwich, während ihr über die Hausaufgaben lästert.",
  komoren: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du eine Banane oder ein Stück Kokosbrot, während ihr über die Hausaufgaben lästert.",
  dschibuti: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Baguette oder ein Sambusa, während ihr über die Hausaufgaben lästert.",
  aegypten: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Ta'ameya-Sandwich (ägyptische Falafel) oder ein Stück Fladenbrot mit Fuul (Bohnenmus), während ihr über die Hausaufgaben lästert.",
  irak: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Samoon-Brötchen mit Käse oder Kahi mit Sirup, während ihr über die Hausaufgaben lästert.",
  jordanien: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Manakish (Fladenbrot mit Za'atar) oder ein Falafel-Sandwich, während ihr über die Hausaufgaben lästert.",
  kuwait: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du in der Kantine ein Sandwich oder einen Sambosa, während ihr über die Hausaufgaben lästert.",
  libanon: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Manakish (Fladenbrot mit Za'atar oder Käse) oder ein Ka'ak-Brötchen, während ihr über die Hausaufgaben lästert.",
  libyen: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Fladenbrot mit Bazin oder ein Sfinz-Krapfen, während ihr über die Hausaufgaben lästert.",
  mauretanien: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Fladenbrot mit Datteln oder eine Handvoll gerösteter Erdnüsse, während ihr über die Hausaufgaben lästert.",
  marokko: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Msemen (Fladen) mit Honig oder ein Sardinen-Sandwich, während ihr über die Hausaufgaben lästert.",
  oman: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du in der Kantine einen Sambosa oder ein Käse-Sandwich, während ihr über die Hausaufgaben lästert.",
  palaestina: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Manakish (Fladenbrot mit Za'atar) oder ein Falafel-Sandwich, während ihr über die Hausaufgaben lästert.",
  katar: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du in der Schulkantine ein Sandwich oder einen Sambosa, während ihr über die Hausaufgaben lästert.",
  saudi: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Shawarma-Sandwich oder einen Sambosa aus der Kantine, während ihr über die Hausaufgaben lästert.",
  somalia: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du einen Sambuus oder ein Stück Anjero (Fladen), während ihr über die Hausaufgaben lästert.",
  sudan: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Kisra (dünnes Fladenbrot) mit Ful oder ein Sambosa, während ihr über die Hausaufgaben lästert.",
  syrien: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Manakish (Fladenbrot mit Za'atar) oder ein Falafel-Sandwich, während ihr über die Hausaufgaben lästert.",
  tunesien: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du eine Fricassée oder ein Thunfisch-Baguette, während ihr über die Hausaufgaben lästert.",
  vae: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du in der Schulkantine ein Chapati-Wrap oder einen Sambosa, während ihr über die Hausaufgaben lästert.",
  jemen: "Heute ist ein ganz gewöhnlicher Schultag. In der Pause isst du ein Stück Malawah-Fladen mit Honig oder ein Bint-al-Sahn, während ihr über die Hausaufgaben lästert.",
};

const tagStories: Record<string, string> = {
  fest: "Heute ist ein besonderer Tag: Im ganzen Ort wird ein Fest gefeiert, sei es das Ende des Ramadan (Eid al-Fitr), eine Hochzeit oder ein nationaler Feiertag. Die Straßen sind mit bunten Lichtern geschmückt, es duftet nach Baklava und gegrilltem Fleisch, überall erklingt Musik von Oud und Trommeln.",
  ferien: "Heute ist ein freier Tag mitten in den Sommerferien. Kein Wecker, keine Hausaufgaben, nur Zeit, um draußen mit Freunden zu spielen, bis die Nachmittagshitze zu stark wird und alle sich in den Schatten zurückziehen.",
};

// Hobby "tanz" is now region-aware so Dabke is only used in Levant countries
const hobbyTanzByLand: Record<string, string> = {
  libanon: "Am liebsten tanzt und musizierst du. Ob die energiegeladene Dabke, bei der sich alle im Kreis an den Händen halten, oder die Klänge der Oud – wenn die Musik beginnt, kannst du einfach nicht stillstehen.",
  syrien: "Am liebsten tanzt und musizierst du. Ob die energiegeladene Dabke, bei der sich alle im Kreis an den Händen halten, oder die Klänge der Oud – wenn die Musik beginnt, kannst du einfach nicht stillstehen.",
  jordanien: "Am liebsten tanzt und musizierst du. Ob die energiegeladene Dabke, bei der sich alle im Kreis an den Händen halten, oder die Klänge der Oud – wenn die Musik beginnt, kannst du einfach nicht stillstehen.",
  palaestina: "Am liebsten tanzt und musizierst du. Ob die energiegeladene Dabke, bei der sich alle im Kreis an den Händen halten, oder die Klänge der Oud – wenn die Musik beginnt, kannst du einfach nicht stillstehen.",
  irak: "Am liebsten tanzt und musizierst du. Die Klänge von Oud, Joza und Trommeln des Maqam al-Iraqi begleiten dich, und bei Festen tanzt du mit Freunden den energiegeladenen Chobi.",
  aegypten: "Am liebsten tanzt und musizierst du. Die Rhythmen der Tabla und die Klänge von Oud und Ney begleiten dich, und bei Hochzeiten tanzt du mit Freunden bis tief in die Nacht.",
  marokko: "Am liebsten tanzt und musizierst du. Die tranceartigen Klänge der Gnawa-Musik und die kraftvollen Trommeln bei Festen im Atlas begeistern dich immer wieder.",
  algerien: "Am liebsten tanzt und musizierst du. Die pulsierenden Rhythmen des Raï und die Trommeln der Chaabi-Musik ziehen dich in ihren Bann.",
  tunesien: "Am liebsten tanzt und musizierst du. Ob der lebendige Mezoued mit seinem Dudelsackklang oder die klassischen Melodien des Malouf – wenn die Musik beginnt, kannst du nicht stillstehen.",
  libyen: "Am liebsten tanzt und musizierst du. Bei Festen tanzt du zu den Trommeln des Zamzama und den Klängen traditioneller Berber- und arabischer Musik.",
  sudan: "Am liebsten tanzt und musizierst du. Die Klänge der Tanbur-Laute und die Trommeln bei den nubischen Festen bringen dich sofort in Bewegung.",
  somalia: "Am liebsten tanzt und musizierst du. Der Dhaanto mit seinen kraftvollen Bewegungen und die Trommeln bei Familienfeiern gehören zu deinen Lieblingsmomenten.",
  mauretanien: "Am liebsten tanzt und musizierst du. Die Klänge der Tidinit-Laute und der Ardin-Harfe der Griots faszinieren dich, seit du klein bist.",
  komoren: "Am liebsten tanzt und musizierst du. Bei den Twarab-Abenden mit Oud und Geige tanzt du mit deinen Cousinen und Cousins bis spät in die Nacht.",
  dschibuti: "Am liebsten tanzt und musizierst du. Die Klänge der Somali- und Afar-Musik mit Trommeln und Gesang begleiten dich bei jedem Fest.",
  jemen: "Am liebsten tanzt und musizierst du. Der traditionelle Bara'a-Tanz mit dem Krummdolch Jambiya im Kreis begeistert dich, seit du zum ersten Mal zugesehen hast.",
  saudi: "Am liebsten tanzt und musizierst du. Der traditionelle Ardah-Tanz mit Trommeln, Schwertern und Gedichten gehört zu den kraftvollsten Momenten bei jedem Fest.",
  vae: "Am liebsten tanzt und musizierst du. Der Al-Ayyala mit Trommeln, Gesang und tanzenden Reihen aus Männern gehört zu den prächtigsten Momenten bei jedem Fest.",
  katar: "Am liebsten tanzt und musizierst du. Der traditionelle Al-Ardha mit Trommeln, Gesang und Schwertbewegungen ist bei jedem Nationalfeiertag dein Highlight.",
  kuwait: "Am liebsten tanzt und musizierst du. Die Rhythmen der Sawt-Musik und der Trommelklang beim Ardah begleiten dich bei jedem Fest.",
  bahrain: "Am liebsten tanzt und musizierst du. Die alten Fidjeri-Lieder der Perlentaucher und die Trommeln bei Festen ziehen dich in ihren Bann.",
  oman: "Am liebsten tanzt und musizierst du. Der traditionelle Razha mit Trommeln, Schwertern und Gesang ist bei jedem Fest dein Lieblingsmoment.",
};

const hobbyStories: Record<string, string> = {
  fussball: "Deine große Leidenschaft ist Fußball. Fußball ist in der gesamten arabischen Welt eine der beliebtesten Sportarten überhaupt, sobald es die Zeit erlaubt, spielst du mit Freunden auf jedem freien Fleckchen Erde, manchmal träumst du sogar von einer Karriere als Profi.",
  kunst: "Deine Leidenschaft ist das Kunsthandwerk. Mit Ton, Fäden oder feinem Pinsel gestaltest du kleine Kunstwerke wie geometrische Mosaike, gewebte Teppiche oder kunstvolle arabische Kalligrafie – eine Handwerkskunst, die seit Jahrhunderten weitergegeben wird.",
  kochen: "Am glücklichsten bist du in der Küche. Du liebst es, mit deiner Familie kleine Mezze-Schälchen vorzubereiten, Teig für Baklava hauchdünn auszurollen oder einen großen Topf für ein Familienfest zu kochen.",
};

const countryFacts: Record<string, string> = {
  algerien: "Algerien ist mit rund 2,38 Millionen km² das flächenmäßig größte Land Afrikas und der arabischen Welt, über 80% der Fläche sind Sahara-Wüste.",
  bahrain: "Bahrain ist ein Inselstaat und mit knapp 780 km² eines der kleinsten Länder der Welt, jahrhundertelang war es berühmt für seine Naturperlen.",
  komoren: "Die Komoren bestehen aus mehreren Vulkaninseln im Indischen Ozean, hier wird rund 80% des weltweiten Ylang-Ylang für Parfüm angebaut.",
  dschibuti: "Der Assal-See in Dschibuti liegt etwa 155 Meter unter dem Meeresspiegel und ist der tiefste Punkt Afrikas, sein Wasser ist fast zehnmal salziger als das Meer.",
  aegypten: "Die Pyramiden von Gizeh sind über 4500 Jahre alt und das einzige der sieben antiken Weltwunder, das heute noch fast vollständig erhalten ist.",
  irak: "Im Zweistromland zwischen Euphrat und Tigris entstand vor über 5000 Jahren eine der ersten Hochkulturen der Menschheit, hier wurde vermutlich auch die Schrift erfunden.",
  jordanien: "Die Felsenstadt Petra wurde vor über 2000 Jahren direkt aus rosafarbenem Sandstein gehauen, das Tote Meer an Jordaniens Grenze liegt an der tiefsten Landstelle der Erde.",
  kuwait: "Kuwait besitzt eines der größten Ölvorkommen der Welt, der Al-Hamra-Turm in Kuwait-Stadt zählt mit seiner unregelmäßig gedrehten Form zu den höchsten Betongebäuden der Welt.",
  libanon: "Die Zeder ist das Nationalsymbol des Libanon und ziert die Flagge, manche der übrig gebliebenen Zedern im Gebirge sind über 1000 Jahre alt.",
  libyen: "Die Oasenstadt Ghadames in Libyen wird wegen ihrer engen, überdachten Gassen und Lehmhäuser 'Perle der Wüste' genannt und gehört zum UNESCO-Weltkulturerbe.",
  mauretanien: "Die 'Augen der Sahara' (Richat-Struktur) in Mauretanien sind eine riesige, ringförmige Felsformation, die sogar aus dem Weltall gut zu erkennen ist.",
  marokko: "Die Stadt Chefchaouen in Marokko ist komplett in leuchtendem Blau gestrichen, Marokko besitzt außerdem sowohl eine Atlantik- als auch eine Mittelmeerküste.",
  oman: "Oman betreibt seit über 1500 Jahren das Falaj-Bewässerungssystem, ein Netzwerk aus unterirdischen Kanälen, das Wasser aus den Bergen in die Oasen leitet, teils UNESCO-Welterbe.",
  palaestina: "Der Olivenbaum ist ein zentrales Symbol der palästinensischen Kultur, manche Olivenbäume im Westjordanland sind mehrere hundert Jahre alt und werden noch heute jeden Herbst geerntet.",
  katar: "Katar hat eine der weltweit höchsten Konzentrationen an Erdgasvorkommen und war 2022 das erste arabische und nahöstliche Land, das eine Fußball-Weltmeisterschaft ausrichtete.",
  saudi: "Die Rub al-Khali ist mit über 650.000 km² die größte zusammenhängende Sandwüste der Welt, größer als Frankreich.",
  somalia: "Somalia hat mit über 3300 km die längste Festlandküste Afrikas, das Land wird oft das 'Horn von Afrika' genannt, weil seine Form an ein Tierhorn erinnert.",
  sudan: "In Sudan gibt es mehr Pyramiden als in Ägypten, über 200 kleinere, spitzere Pyramiden aus der Zeit des Königreichs Kusch stehen bei Meroe.",
  syrien: "Damaskus gilt als eine der ältesten durchgehend bewohnten Städte der Welt, hier wird seit über 5000 Jahren ohne Unterbrechung gelebt.",
  tunesien: "In der Oasenstadt Tozeur wachsen seit Jahrhunderten Dattelpalmen der Sorte Deglet Nour, die als 'Finger des Lichts' gilt und zu den süßesten Dattelsorten der Welt zählt.",
  vae: "Der Burj Khalifa in Dubai ist mit 828 Metern das höchste von Menschen gebaute Gebäude der Welt, so hoch wie mehr als 160 übereinandergestapelte Doppeldeckerbusse.",
  jemen: "Die Altstadt von Sanaa ist für ihre jahrhundertealten Turmhäuser aus Lehmziegeln mit kunstvollen weißen Gipsverzierungen bekannt und gehört zum UNESCO-Weltkulturerbe.",
};

const resultEmojis: Record<string, string> = {
  algerien: "🏜️", bahrain: "🦪", komoren: "🌋", dschibuti: "🐫", aegypten: "🐫",
  irak: "🌾", jordanien: "🏛️", kuwait: "🛢️", libanon: "🌲", libyen: "🏜️",
  mauretanien: "🐫", marokko: "🕌", oman: "⛵", palaestina: "🫒", katar: "🏗️",
  saudi: "🏜️", somalia: "🐪", sudan: "🔺", syrien: "🕌", tunesien: "🌴",
  vae: "🌆", jemen: "🧱",
};

// ---------- ORNAMENTS ----------

function ArabesqueBackground() {
  // Repeating geometric Islamic star pattern in gold on midnight background
  const svg = encodeURIComponent(`
<svg xmlns='http://www.w3.org/2000/svg' width='120' height='120' viewBox='0 0 120 120'>
  <g fill='none' stroke='#d4af6a' stroke-width='0.7' opacity='0.35'>
    <polygon points='60,10 70,40 100,40 76,58 86,88 60,70 34,88 44,58 20,40 50,40'/>
    <circle cx='60' cy='60' r='28'/>
    <circle cx='60' cy='60' r='14'/>
    <polygon points='60,32 68,60 60,88 52,60'/>
    <polygon points='32,60 60,52 88,60 60,68'/>
  </g>
</svg>`);
  return (
    <div
      aria-hidden
      className="pointer-events-none absolute inset-0 opacity-40"
      style={{ backgroundImage: `url("data:image/svg+xml;utf8,${svg}")`, backgroundSize: "180px 180px" }}
    />
  );
}

function CornerOrnament({ position }: { position: "tl" | "tr" | "bl" | "br" }) {
  const rot = { tl: 0, tr: 90, br: 180, bl: 270 }[position];
  const pos: React.CSSProperties = {
    position: "absolute",
    width: 64,
    height: 64,
    transform: `rotate(${rot}deg)`,
    ...(position.includes("t") ? { top: 8 } : { bottom: 8 }),
    ...(position.includes("l") ? { left: 8 } : { right: 8 }),
  };
  return (
    <svg viewBox="0 0 64 64" style={pos} aria-hidden>
      <g fill="none" stroke="#d4af6a" strokeWidth="1.2">
        <path d="M4 4 L4 28 M4 4 L28 4" />
        <path d="M10 4 Q28 4 28 22" />
        <circle cx="10" cy="10" r="2.5" fill="#d4af6a" />
        <path d="M4 34 Q14 34 18 24" />
      </g>
    </svg>
  );
}

function GoldDivider() {
  return (
    <div className="flex items-center justify-center gap-3 my-4 opacity-80">
      <span className="h-px w-16 bg-gradient-to-r from-transparent to-[#d4af6a]" />
      <svg width="28" height="14" viewBox="0 0 28 14" aria-hidden>
        <path d="M0 7 L7 0 L14 7 L21 0 L28 7 L21 14 L14 7 L7 14 Z" fill="#d4af6a" />
      </svg>
      <span className="h-px w-16 bg-gradient-to-l from-transparent to-[#d4af6a]" />
    </div>
  );
}

// ---------- APP ----------

type Step = 0 | 1 | 2 | 3 | 4 | 5 | 6 | "result";
type State = {
  land: string | null;
  gender: string | null;
  ort: string | null;
  leben: string | null;
  tag: string | null;
  hobby: string | null;
};

const TOTAL_STEPS = 6;
const order: (keyof State)[] = ["land", "gender", "ort", "leben", "tag", "hobby"];

function ArabWorldApp() {
  const [step, setStep] = useState<Step>(0);
  const [state, setState] = useState<State>({
    land: null, gender: null, ort: null, leben: null, tag: null, hobby: null,
  });

  useEffect(() => { window.scrollTo(0, 0); }, [step]);

  const countryNames = useMemo(
    () => Object.fromEntries(countries.map((c) => [c.key, `${c.flag} ${c.name}`])),
    []
  );
  const locationLabels = useMemo(() => {
    const map: Record<string, string> = {};
    Object.keys(locations).forEach((k) => {
      locations[k].forEach((loc) => (map[`${k}_${loc.key}`] = `${loc.icon} ${loc.label}`));
    });
    return map;
  }, []);

  function select<K extends keyof State>(key: K, value: string) {
    const next: State = { ...state, [key]: value };
    setState(next);
    const idx = order.indexOf(key);
    const nextStep = idx + 2;
    if (nextStep <= TOTAL_STEPS) setStep(nextStep as Step);
    else setStep("result");
  }

  function reset() {
    setState({ land: null, gender: null, ort: null, leben: null, tag: null, hobby: null });
    setStep(0);
  }

  return (
    <div className="relative min-h-screen overflow-x-hidden text-[#f6ecd6]"
      style={{
        fontFamily: "'Cairo', 'Segoe UI', sans-serif",
        background:
          "radial-gradient(ellipse at 20% 0%, #1e6b6b 0%, transparent 55%), radial-gradient(ellipse at 100% 100%, #b8823a 0%, transparent 45%), linear-gradient(160deg, #0a1a2e 0%, #0d2f3a 45%, #1a3c3a 100%)",
      }}
    >
      <ArabesqueBackground />

      <div className="relative z-10 mx-auto flex min-h-screen max-w-5xl flex-col items-center px-4 py-6 sm:py-10">
        {step !== 0 && step !== "result" && <ProgressMosaic step={step as number} />}

        {step === 0 && <ScreenWelcome onStart={() => setStep(1)} />}
        {step === 1 && (
          <Screen label="Schritt 1 von 6" title="In welchem Land lebst du?">
            <CardGrid>
              {countries.map((c) => (
                <ChoiceCard key={c.key} icon={c.flag} label={c.name} onClick={() => select("land", c.key)} />
              ))}
            </CardGrid>
          </Screen>
        )}
        {step === 2 && (
          <Screen label="Schritt 2 von 6" title="Wer bist du?">
            <CardGrid two>
              <ChoiceCard icon="👧" label="Ein Mädchen" onClick={() => select("gender", "maedchen")} />
              <ChoiceCard icon="👦" label="Ein Junge" onClick={() => select("gender", "junge")} />
            </CardGrid>
          </Screen>
        )}
        {step === 3 && state.land && (
          <Screen label="Schritt 3 von 6" title="Wo genau lebst du?">
            <CardGrid two>
              {locations[state.land].map((loc) => (
                <ChoiceCard key={loc.key} icon={loc.icon} label={loc.label} sub={loc.sub} onClick={() => select("ort", loc.key)} />
              ))}
            </CardGrid>
          </Screen>
        )}
        {step === 4 && (
          <Screen label="Schritt 4 von 6" title="Wie lebt deine Familie?">
            <CardGrid>
              <ChoiceCard icon="💎" label="Wohlhabend" onClick={() => select("leben", "wohlhabend")} />
              <ChoiceCard icon="🏡" label="Mittelschicht" onClick={() => select("leben", "mittelschicht")} />
              <ChoiceCard icon="🌾" label="Einfache Verhältnisse" onClick={() => select("leben", "einfach")} />
            </CardGrid>
          </Screen>
        )}
        {step === 5 && (
          <Screen label="Schritt 5 von 6" title="Was für ein Tag ist heute?">
            <CardGrid>
              <ChoiceCard icon="🏫" label="Ein ganz normaler Schultag" onClick={() => select("tag", "schultag")} />
              <ChoiceCard icon="🎉" label="Ein Fest oder Feiertag" onClick={() => select("tag", "fest")} />
              <ChoiceCard icon="☀️" label="Ein Ferientag" onClick={() => select("tag", "ferien")} />
            </CardGrid>
          </Screen>
        )}
        {step === 6 && (
          <Screen label="Schritt 6 von 6" title="Was ist deine Lieblingsbeschäftigung?">
            <CardGrid>
              <ChoiceCard icon="⚽" label="Fußball" onClick={() => select("hobby", "fussball")} />
              <ChoiceCard icon="🪘" label="Musik & Tanz" onClick={() => select("hobby", "tanz")} />
              <ChoiceCard icon="🎨" label="Kunsthandwerk" onClick={() => select("hobby", "kunst")} />
              <ChoiceCard icon="🍲" label="Kochen" onClick={() => select("hobby", "kochen")} />
            </CardGrid>
          </Screen>
        )}
        {step === "result" && state.land && state.gender && state.ort && state.leben && state.tag && state.hobby && (
          <ResultScreen
            state={{ land: state.land, gender: state.gender, ort: state.ort, leben: state.leben, tag: state.tag, hobby: state.hobby }}
            countryNames={countryNames}
            locationLabels={locationLabels}
            onReset={reset}
          />
        )}
      </div>
    </div>
  );
}

function ProgressMosaic({ step }: { step: number }) {
  return (
    <div className="mb-8 flex w-full max-w-xl items-center justify-center gap-2">
      {Array.from({ length: TOTAL_STEPS }).map((_, i) => {
        const done = i < step - 1;
        const current = i === step - 1;
        return (
          <div key={i} className="flex-1 flex justify-center">
            <div
              className="h-3 w-3 sm:h-4 sm:w-4 transition-all duration-500"
              style={{
                transform: "rotate(45deg)",
                background: done
                  ? "linear-gradient(135deg, #f0c674, #b8823a)"
                  : current
                  ? "linear-gradient(135deg, #e6d5a8, #d4af6a)"
                  : "rgba(212, 175, 106, 0.15)",
                border: current ? "1px solid #f6ecd6" : "1px solid rgba(212,175,106,0.35)",
                boxShadow: done || current ? "0 0 12px rgba(240,198,116,0.5)" : "none",
              }}
            />
          </div>
        );
      })}
    </div>
  );
}

function Screen({ label, title, children }: { label: string; title: string; children: React.ReactNode }) {
  return (
    <section className="w-full animate-[fadeUp_.5s_ease] flex flex-col items-center">
      <div
        className="text-[0.7rem] sm:text-xs font-semibold uppercase tracking-[0.3em] mb-2 text-[#d4af6a]"
        style={{ textShadow: "0 0 8px rgba(212,175,106,0.4)" }}
      >
        ✦ {label} ✦
      </div>
      <h2
        className="text-center text-2xl sm:text-4xl font-normal mb-2 text-[#f6ecd6]"
        style={{
          fontFamily: "'Amiri', 'Cormorant Garamond', serif",
          textShadow: "0 2px 12px rgba(0,0,0,0.5)",
          letterSpacing: "0.02em",
        }}
      >
        {title}
      </h2>
      <GoldDivider />
      <div className="w-full mt-2">{children}</div>
      <style>{`@keyframes fadeUp{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:translateY(0)}}`}</style>
    </section>
  );
}

function CardGrid({ children, two }: { children: React.ReactNode; two?: boolean }) {
  return (
    <div
      className="grid gap-3 sm:gap-4 w-full"
      style={{
        gridTemplateColumns: two
          ? "repeat(auto-fit, minmax(160px, 1fr))"
          : "repeat(auto-fit, minmax(150px, 1fr))",
      }}
    >
      {children}
    </div>
  );
}

function ChoiceCard({ icon, label, sub, onClick }: { icon: string; label: string; sub?: string; onClick: () => void }) {
  return (
    <button
      onClick={onClick}
      className="group relative overflow-hidden text-center transition-all duration-300 hover:-translate-y-1 active:scale-[0.97]"
      style={{
        background: "linear-gradient(180deg, rgba(246,236,214,0.98) 0%, rgba(230,213,168,0.95) 100%)",
        borderRadius: "22px 22px 22px 22px / 60px 60px 22px 22px", // mihrab arch top
        padding: "20px 12px 16px",
        minHeight: 140,
        border: "1.5px solid #d4af6a",
        boxShadow:
          "0 8px 24px rgba(0,0,0,0.35), inset 0 1px 0 rgba(255,255,255,0.6), inset 0 0 0 4px rgba(212,175,106,0.15)",
        color: "#1a3c3a",
      }}
    >
      <span
        aria-hidden
        className="pointer-events-none absolute inset-0 opacity-0 group-hover:opacity-100 transition-opacity duration-500"
        style={{
          background:
            "radial-gradient(circle at 50% 0%, rgba(240,198,116,0.55) 0%, transparent 60%)",
        }}
      />
      <div className="relative flex flex-col items-center justify-center gap-2">
        <div className="text-4xl sm:text-5xl leading-none" style={{ filter: "drop-shadow(0 2px 4px rgba(0,0,0,0.2))" }}>
          {icon}
        </div>
        <div
          className="font-bold text-sm sm:text-base"
          style={{ fontFamily: "'Cormorant Garamond', serif", letterSpacing: "0.02em" }}
        >
          {label}
        </div>
        {sub && <div className="text-[11px] sm:text-xs opacity-70 italic px-1">{sub}</div>}
      </div>
    </button>
  );
}

function ScreenWelcome({ onStart }: { onStart: () => void }) {
  return (
    <section className="w-full flex flex-col items-center animate-[fadeUp_.6s_ease]">
      <div className="relative mb-4">
        <svg width="180" height="140" viewBox="0 0 180 140" aria-hidden>
          {/* Mihrab arch silhouette */}
          <defs>
            <linearGradient id="gold" x1="0" x2="0" y1="0" y2="1">
              <stop offset="0%" stopColor="#f7dc8a" />
              <stop offset="100%" stopColor="#b8823a" />
            </linearGradient>
          </defs>
          <path
            d="M90 6 C130 6 150 32 150 68 L150 130 L30 130 L30 68 C30 32 50 6 90 6 Z"
            fill="none"
            stroke="url(#gold)"
            strokeWidth="2.2"
          />
          <path
            d="M90 22 C120 22 138 44 138 72 L138 118 L42 118 L42 72 C42 44 60 22 90 22 Z"
            fill="none"
            stroke="#d4af6a"
            strokeWidth="1"
            opacity="0.6"
          />
          <text x="90" y="92" textAnchor="middle" fontSize="52" style={{ filter: "drop-shadow(0 4px 8px rgba(0,0,0,0.5))" }}>🕌</text>
          <circle cx="60" cy="30" r="2" fill="#f7dc8a" />
          <circle cx="120" cy="30" r="2" fill="#f7dc8a" />
          <text x="150" y="18" fontSize="18">🌙</text>
          <text x="18" y="18" fontSize="14">⭐</text>
        </svg>
      </div>

      <div className="text-[0.7rem] font-semibold uppercase tracking-[0.35em] mb-3 text-[#d4af6a]">
        ✦ Ahlan wa Sahlan ✦
      </div>

      <h1
        className="text-center text-3xl sm:text-5xl font-normal mb-3 text-[#f6ecd6]"
        style={{
          fontFamily: "'Amiri', 'Cormorant Garamond', serif",
          letterSpacing: "0.02em",
          textShadow: "0 3px 16px rgba(0,0,0,0.6), 0 0 30px rgba(212,175,106,0.2)",
        }}
      >
        Willkommen in der<br className="sm:hidden" /> arabischen Welt
      </h1>

      <GoldDivider />

      <p className="max-w-xl text-center text-base sm:text-lg leading-relaxed text-[#e6d5a8] mb-6 px-2">
        Wähle eines von 22 arabischen Ländern, schlüpfe in das Leben eines Kindes und
        entdecke, wie unterschiedlich der Alltag von Marokko bis zum Jemen, von
        Mauretanien bis zum Irak sein kann. Triff sechs Entscheidungen und erlebe deine
        ganz persönliche Geschichte.
      </p>

      <div className="text-center text-lg sm:text-xl tracking-[6px] mb-8 opacity-90">
        🇲🇦 🇩🇿 🇹🇳 🇱🇾 🇪🇬 🇸🇩 🇸🇴 🇩🇯 🇰🇲 🇲🇷
        <br />
        🇱🇧 🇸🇾 🇯🇴 🇵🇸 🇮🇶 🇸🇦 🇰🇼 🇶🇦 🇧🇭 🇦🇪 🇴🇲 🇾🇪
      </div>

      <OrnateButton onClick={onStart}>✦ Abenteuer beginnen ✦</OrnateButton>
    </section>
  );
}

function OrnateButton({ children, onClick, variant = "gold" }: {
  children: React.ReactNode;
  onClick: () => void;
  variant?: "gold" | "turquoise";
}) {
  const gold = variant === "gold";
  return (
    <button
      onClick={onClick}
      className="relative group px-10 py-5 text-lg sm:text-xl font-semibold transition-transform duration-200 active:scale-[0.96] hover:-translate-y-0.5"
      style={{
        fontFamily: "'Cormorant Garamond', serif",
        letterSpacing: "0.08em",
        color: gold ? "#1a2e3a" : "#f6ecd6",
        background: gold
          ? "linear-gradient(180deg, #f7dc8a 0%, #d4af6a 50%, #b8823a 100%)"
          : "linear-gradient(180deg, #1e6b6b 0%, #0d4a4a 100%)",
        borderRadius: "40px 40px 40px 40px / 80px 80px 40px 40px",
        border: gold ? "2px solid #8a5f24" : "2px solid #d4af6a",
        boxShadow:
          "0 12px 28px rgba(0,0,0,0.45), inset 0 2px 0 rgba(255,255,255,0.4), inset 0 -2px 0 rgba(0,0,0,0.2)",
      }}
    >
      <span
        aria-hidden
        className="absolute inset-1 rounded-[36px_36px_36px_36px_/_75px_75px_36px_36px] pointer-events-none"
        style={{ border: `1px solid ${gold ? "rgba(255,255,255,0.35)" : "#d4af6a"}` }}
      />
      <span className="relative">{children}</span>
    </button>
  );
}

function ResultScreen({
  state, countryNames, locationLabels, onReset,
}: {
  state: { [K in keyof State]: NonNullable<State[K]> };
  countryNames: Record<string, string>;
  locationLabels: Record<string, string>;
  onReset: () => void;
}) {
  const baseKey = `${state.land}_${state.ort}_${state.leben}`;
  const base = baseStories[baseKey] || "Deine Geschichte wird noch geschrieben.";
  const tagText =
    state.tag === "schultag"
      ? tagStorySchultagByLand[state.land] ?? tagStorySchultagByLand.aegypten
      : tagStories[state.tag];
  const hobbyText =
    state.hobby === "tanz"
      ? hobbyTanzByLand[state.land] ?? hobbyTanzByLand.libanon
      : hobbyStories[state.hobby];

  const tagLabels = {
    gender: { maedchen: "👧 Mädchen", junge: "👦 Junge" } as Record<string, string>,
    leben: { wohlhabend: "💎 Wohlhabend", mittelschicht: "🏡 Mittelschicht", einfach: "🌾 Einfache Verhältnisse" } as Record<string, string>,
    tag: { schultag: "🏫 Schultag", fest: "🎉 Fest", ferien: "☀️ Ferien" } as Record<string, string>,
    hobby: { fussball: "⚽ Fußball", tanz: "🪘 Musik & Tanz", kunst: "🎨 Kunsthandwerk", kochen: "🍲 Kochen" } as Record<string, string>,
  };

  const tags = [
    countryNames[state.land],
    tagLabels.gender[state.gender],
    locationLabels[`${state.land}_${state.ort}`],
    tagLabels.leben[state.leben],
    tagLabels.tag[state.tag],
    tagLabels.hobby[state.hobby],
  ];

  return (
    <section className="w-full flex flex-col items-center animate-[fadeUp_.6s_ease]">
      <div
        className="text-6xl sm:text-7xl mb-4"
        style={{ filter: "drop-shadow(0 8px 16px rgba(0,0,0,0.5))" }}
      >
        {resultEmojis[state.land] || "🕌"}
      </div>

      <div
        className="relative w-full"
        style={{
          background:
            "linear-gradient(180deg, #fbf5e6 0%, #f3e6c4 100%)",
          borderRadius: "28px 28px 28px 28px / 80px 80px 28px 28px",
          padding: "40px 24px 28px",
          color: "#1a2e3a",
          boxShadow:
            "0 20px 50px rgba(0,0,0,0.5), inset 0 0 0 2px #d4af6a, inset 0 0 0 8px rgba(212,175,106,0.15)",
        }}
      >
        <CornerOrnament position="tl" />
        <CornerOrnament position="tr" />
        <CornerOrnament position="bl" />
        <CornerOrnament position="br" />

        <h3
          className="text-center text-2xl sm:text-3xl mb-2"
          style={{
            fontFamily: "'Amiri', 'Cormorant Garamond', serif",
            color: "#0d4a4a",
            letterSpacing: "0.02em",
          }}
        >
          Dein Alltag in {countryNames[state.land].split(" ").slice(1).join(" ")}
        </h3>

        <GoldDividerDark />

        <div className="flex flex-wrap justify-center gap-2 mb-6">
          {tags.map((t, i) => (
            <span
              key={i}
              className="px-3 py-1 text-xs sm:text-sm font-semibold"
              style={{
                background: "linear-gradient(180deg, #1e6b6b 0%, #0d4a4a 100%)",
                color: "#f6ecd6",
                borderRadius: "16px",
                border: "1px solid #d4af6a",
                boxShadow: "inset 0 1px 0 rgba(255,255,255,0.15)",
              }}
            >
              {t}
            </span>
          ))}
        </div>

        <div
          className="space-y-3 text-base sm:text-lg leading-relaxed text-left"
          style={{ fontFamily: "'Cairo', sans-serif", color: "#2a2a2a" }}
        >
          <p>{base}</p>
          <p>{tagText}</p>
          <p>{hobbyText}</p>
        </div>

        <div
          className="mt-6 p-4 sm:p-5"
          style={{
            background: "linear-gradient(135deg, #fef7e0 0%, #f5e4b0 100%)",
            borderLeft: "5px solid #b8823a",
            borderRadius: "0 16px 16px 0",
            boxShadow: "inset 0 0 0 1px rgba(212,175,106,0.4)",
          }}
        >
          <div
            className="text-xs font-bold uppercase tracking-[0.2em] mb-1"
            style={{ color: "#8a5f24", fontFamily: "'Cormorant Garamond', serif" }}
          >
            ✦ Krasser Fakt ✦
          </div>
          <div className="text-sm sm:text-base leading-relaxed" style={{ color: "#3a2a15" }}>
            {countryFacts[state.land]}
          </div>
        </div>
      </div>

      <div className="mt-8 w-full flex justify-center">
        <OrnateButton onClick={onReset} variant="turquoise">
          🔄 Nächster Spieler
        </OrnateButton>
      </div>
    </section>
  );
}

function GoldDividerDark() {
  return (
    <div className="flex items-center justify-center gap-3 my-3">
      <span className="h-px w-20 bg-gradient-to-r from-transparent to-[#b8823a]" />
      <svg width="28" height="14" viewBox="0 0 28 14" aria-hidden>
        <path d="M0 7 L7 0 L14 7 L21 0 L28 7 L21 14 L14 7 L7 14 Z" fill="#b8823a" />
      </svg>
      <span className="h-px w-20 bg-gradient-to-l from-transparent to-[#b8823a]" />
    </div>
  );
}
