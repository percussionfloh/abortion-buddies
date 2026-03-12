<script setup>
const localePath = useLocalePath();

const { t } = useI18n();

const columns = [
    {
        label: t('importantLinks'),
        children: [
            {
                label: t('start'),
                to: localePath('index'),
            },
            {
                label: t('faq'),
                to: localePath('faq'),
            },
        ],
    },
    {
        label: t('sitemap'),
        children: [
            {
                label: t('legalNotice'),
                to: localePath('legal-notice'),
            },
        ],
    },
];
</script>
@@ -41,7 +31,7 @@
                <template #right>
                        <div>
                            <div class="flex justify-end">
                                    Halo
                            </div>
                        </div>
                    </template>