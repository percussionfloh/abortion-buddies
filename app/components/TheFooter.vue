<script setup>
const localePath = useLocalePath();
const { t } = useI18n();

const columns = [
    {
        label: t('importantLinks'),
        children: [
            {
                label: t('legalNotice'),
                to: localePath('legalNotice'),
            },
        ]
    }
];
</script>


<template>
    <UFooter class="bg-pattern">
        <template #top>
            <UContainer>
                <UFooterColumns :columns="columns" :ui="{
                    list: 'grid grid-cols-2 gap-x-2 space-y-0 mt-3',
                    link: 'text-white text-base',
                    label: 'text-white text-lg',
                }">
                <template #right>
                        <div>
                            <div class="flex justify-end">
                                <img src="../assets/abortionbuddy.jpg" class="max-h-47.5" alt="Abortion-Buddy-Logo" />
                            </div>
                        </div>
                    </template>
                </UFooterColumns>
            </UContainer>
        </template>
    </UFooter>
</template>

