<script setup lang="ts">
/* Import modules. */
import { ref } from 'vue'

const milestones = ref([])

milestones.value.push({
    id: '30e46179-414c-4673-a2f5-860a8161c3a2',
    title: `Launch NexaJS Library + SDK`,
    status: 'complete',
    summary: `A complete suite of Modules and Tools for Nexa's JavaScript builders.`,
    period: '1H 2023',
})

milestones.value.push({
    id: '0c869a8c-136f-441e-aba5-021d4cb879d0',
    title: `Launch PyNexa Library`,
    status: 'pending',
    summary: `A complete suite of Modules and Tools for Nexa's Python builders.`,
    period: '1H 2023',
})

milestones.value.push({
    id: '2a163a9d-6f67-4785-8bed-03b4407b0788',
    title: `Launch NexaRs Library`,
    status: 'pending',
    summary: `A complete suite of Modules and Tools for Nexa's Rust builders.`,
    period: '1H 2023',
})

milestones.value.push({
    id: '0ece6cc9-5a3a-4058-83bc-0be2bd778b3d',
    title: `Launch Awesome Nexa List + Web Portal`,
    status: 'complete',
    summary: `A curated catalog of the BEST of NEXA.`,
    period: '1H 2023',
})

milestones.value.push({
    id: '89de5b8e-f9ad-459d-8fa5-0d3b2366c842',
    title: `Launch Causes.Cash Platform`,
    status: 'pending',
    summary: `Decentralized, Non-custodial Crowdfunding`,
    period: '1H 2023',
})

milestones.value.push({
    id: 'e52d04dc-34ab-4e17-aae4-65f772a5ed4d',
    title: `Re-launch Nexa (Instant) Swap + Nexa Exchange`,
    status: 'pending',
    summary: `A dedicated Nexa exchange supporting 3rd-party platforms (using API keys), including: MEXC, Txbit and Exbitron.`,
    period: '1H 2023',
})

milestones.value.push({
    id: 'cba1438f-627c-4de0-9ea7-944f0e571dc5',
    title: `Launch Nexaverse Testnet`,
    status: 'complete',
    summary: `Avalanche Subnet running an EVM-compatible sidechain with NEX as its native currency.`,
    period: '1H 2023',
})

milestones.value.push({
    id: '267bccbf-61bf-4bd5-a8a1-9545ff4ee092',
    title: `Launch Nexaverse Mainnet`,
    status: 'planning',
    summary: `Avalanche Subnet running an EVM-compatible sidechain with NEX as its native currency.`,
    period: '1H 2023',
})

milestones.value.push({
    id: 'e3645851-36b0-41b2-82cf-ddb3be236448',
    title: `Launch Nexa Shell`,
    status: 'pending',
    summary: `An enterprise-class data provider of ALL things Nexa.`,
    period: '1H 2023',
})

milestones.value.push({
    id: '41115cd4-8f2d-4721-bb20-c76e3f8574fd',
    title: `Re-launch Nexa Rocks!`,
    status: 'pending',
    summary: `Nexa mining pool, supporting "token mining" and featuring the Infinity Pool.`,
    period: '2H 2023',
})

milestones.value.push({
    id: '5b2359f0-5321-445d-8b5a-96cf8d6afdb6',
    title: `Launch Nexa Domains`,
    status: 'planning',
    summary: `An ENS-style registrar for the Nexa community supporting ".nexa" domains.`,
    period: '2H 2023',
})

milestones.value.push({
    id: 'aa508588-67b4-4117-8409-398e97207435',
    title: `Launch Nexa (Cross-chain) Bridge`,
    status: 'planning',
    summary: `A FREE and 100% decentralized, asset bridge to the leading EVM networks, including: Ethereum (ETH), BNB Smart Chain (BSC), Avalanche (AVAX), Polygon (MATIC) and more...`,
    period: '2H 2023',
})

milestones.value.push({
    id: '671e794a-46d3-4fea-9d76-61747d3433e3',
    title: `Begin Ava's DAO Governance`,
    status: 'planning',
    summary: `A Decentralized Autonomous Organization (DAO) to oversee the management of the suite of tools and service being build and deployed for the Nexa blockchain. We will introduce the Crypto world to the first cross-chain Decentralized Autonomous Organization (DAO), spanning: Nexa, Bitcoin, Bitcoin Cash, Avalanche, Binance and more...`,
    period: '1H 2024',
})

milestones.value.push({
    id: '7b46b0c3-ed80-4bb6-b3c3-ab951321275f',
    title: `Launch Nexaverse Mobile App`,
    status: 'planning',
    summary: `A native mobile app for Android and iOS that introduces the world to Web4: Unstoppable Apps.`,
    period: '1H 2024',
})

milestones.value.push({
    id: '64208ca0-e3f5-4c16-b640-d8205d16bc1d',
    title: `Nexaverse Scaling`,
    status: 'planning',
    summary: `Grow usage and utility of the NEW Nexaverse.`,
    period: '2H 2024',
})

milestones.value.push({
    id: 'a6124c53-e49b-436d-8e71-4341a62660a9',
    title: `Launch Ava's #BUIDL (Accelerator)`,
    status: 'planning',
    summary: `Support startups building on Nexa.`,
    period: '1H 2025',
})

</script>

<template>
    <main class="w-11/12 lg:max-w-2xl px-3 py-5 sm:py-0 sm:pt-5 bg-rose-100 border-4 border-rose-500 rounded-xl shadow-lg shadow-inner">
        <h1 class="sm:px-3 text-3xl sm:text-4xl text-rose-600 font-medium tracking-widest uppercase opacity-50">
            Ava's Project Roadmap

            <div class="text-lg sm:text-2xl">
                <h3>2023 - 2025</h3>
            </div>
        </h1>

        <section class="h-96 mt-2 px-2 overflow-y-scroll ">
            <section class="mt-5 py-5">
                <div class="flow-root">
                    <ul role="list" class="-mb-8">

                        <li v-for="milestone of milestones" :key="milestone.id">
                            <div class="relative pb-8">
                                <span class="absolute top-4 left-4 -ml-px h-full w-0.5 bg-rose-500 opacity-20" aria-hidden="true"></span>

                                <div class="relative flex space-x-3">
                                    <div>
                                        <span v-if="milestone.status == 'complete'" class="h-8 w-8 rounded-full bg-green-500 flex items-center justify-center ring-8 ring-white">
                                            <svg class="h-5 w-5 text-white" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                                                <path fill-rule="evenodd" d="M16.704 4.153a.75.75 0 01.143 1.052l-8 10.5a.75.75 0 01-1.127.075l-4.5-4.5a.75.75 0 011.06-1.06l3.894 3.893 7.48-9.817a.75.75 0 011.05-.143z" clip-rule="evenodd" />
                                            </svg>
                                        </span>
                                        <span v-if="milestone.status == 'pending'" class="h-8 w-8 rounded-full bg-yellow-500 flex items-center justify-center ring-8 ring-white">
                                            <svg class="h-7 w-7 text-white" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 12a7.5 7.5 0 0015 0m-15 0a7.5 7.5 0 1115 0m-15 0H3m16.5 0H21m-1.5 0H12m-8.457 3.077l1.41-.513m14.095-5.13l1.41-.513M5.106 17.785l1.15-.964m11.49-9.642l1.149-.964M7.501 19.795l.75-1.3m7.5-12.99l.75-1.3m-6.063 16.658l.26-1.477m2.605-14.772l.26-1.477m0 17.726l-.26-1.477M10.698 4.614l-.26-1.477M16.5 19.794l-.75-1.299M7.5 4.205L12 12m6.894 5.785l-1.149-.964M6.256 7.178l-1.15-.964m15.352 8.864l-1.41-.513M4.954 9.435l-1.41-.514M12.002 12l-3.75 6.495"></path>
                                            </svg>
                                        </span>
                                        <span v-if="milestone.status == 'planning'" class="h-8 w-8 rounded-full bg-purple-500 flex items-center justify-center ring-8 ring-white">
                                            <svg class="ml-0.5 h-5 w-5 text-white" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z"></path>
                                            </svg>
                                        </span>
                                    </div>

                                    <div class="-mt-3 mb-5 pl-2 flex min-w-0 flex-1 justify-between space-x-4 pt-1.5">
                                        <div class="flex flex-col gap-1">
                                            <h2 class="text-xl font-medium text-rose-600">
                                                {{milestone.title}}
                                            </h2>

                                            <span v-if="milestone.status == 'complete'" class="px-3 w-fit text-xs font-medium text-green-900 uppercase bg-green-300 border-2 border-rose-900 rounded-lg">
                                                {{milestone.status}}
                                            </span>
                                            <span v-if="milestone.status == 'pending'" class="px-3 w-fit text-xs font-medium text-yellow-900 uppercase bg-yellow-300 border-2 border-rose-900 rounded-lg">
                                                {{milestone.status}}
                                            </span>
                                            <span v-if="milestone.status == 'planning'" class="px-3 w-fit text-xs font-medium text-purple-900 uppercase bg-purple-300 border-2 border-rose-900 rounded-lg">
                                                {{milestone.status}}
                                            </span>

                                            <p class="text-sm text-gray-600">
                                                {{milestone.summary}}
                                            </p>
                                        </div>

                                        <div class="whitespace-nowrap text-right text-sm text-gray-500">
                                            <time datetime="2020-10-04">
                                                {{milestone.period}}
                                            </time>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </li>

                    </ul>
                </div>

            </section>
        </section>
    </main>
</template>
