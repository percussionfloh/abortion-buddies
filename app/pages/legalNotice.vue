<script setup>
const { t } = useI18n();

useHead({
    title: t('legalNotice'),
});
</script>

<template>
    <UContainer>
        <SectionContainer>
            <section>
                <Heading>{{ $t('legalNotice') }}</Heading>
                <div class="flex flex-col gap-12 my-12">
                    <div>
                        <Subheading>Angaben gemäß § 5 TMG</Subheading>
                        <address>
                            Abortion Buddies e.V.<br>
                            Merzhauserstr<br>
                            79100 Freiburg
                        </address>
                    </div>
                    <div>
                        <Subheading>Kontaktdaten</Subheading>
                        <div>
                            Telefon:
                            <NuxtLink to="tel:004912345678">+49 12345678</NuxtLink>
                        </div>
                        <div>
                            E-Mail:
                            <NuxtLink to="mailto:abortionbuddies.de">abortion@buddies.de</NuxtLink>
                        </div>
                    </div>
                    <div>
                        <Subheading>Haftung für Inhalte</Subheading>
                        <p>
                            Im Sinne von § 7 Absatz 1 TMG sind wir für die eigenen Inhalte auf dieser Webseite
                            verantwortlich. Durch §§ 8 bis einschließlich 10 TMG sind wir aber nicht verpflichtet,
                            gespeicherte oder übermittelte fremde Inhalte zu überwachen oder diese auf Rechtswidrigkeit zu
                            prüfen. Das befreit uns jedoch nicht von der Pflicht, der Sperrung und Entfernung von
                            Informationen nach geltenden Gesetzen nachzukommen.
                        </p>
                    </div>
                </div>
            </section>
        </SectionContainer>
    </UContainer>
</template>

Vor- und Nachnamen des Diensteanbieters.
Bei juristischen Personen (z. B. GmbH, AG) und Personengesellschaften (z. B. GbR, OHG): Firmierung, Firmenbezeichnung, Bezeichnung der Rechtsform sowie mindestens ein ausgeschriebener Vorname sowie der Name des Vertretungsberechtigten.
Adresse (Straße, Hausnummer, Postleitzahl und Ort); bei Gesellschaften der Sitz. Die Angabe eines Postfachs genügt nicht!
E-Mail-Adresse und ein weiteres Kommunikationsmittel, das eine schnelle elektronische Kontaktaufnahme und unmittelbare Kommunikation mit dem Dienstanbieter ermöglicht, z. B. Telefon- oder Faxnummer.
Register und Registernummer, falls ein Eintrag z. B. in ein Handelsregister, Vereinsregister, Partnerschaftsregister oder Genossenschaftsregister besteht.
Angaben zum Stamm- bzw. Grundkapital für Kapitalgesellschaften (z.B. GmbH, AG)