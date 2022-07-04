<template>
    <div class="relative">
        <div></div>
        <TabUppertab class=""/>
        <div class="container mx-auto relative">
        <TabMaintab class="my-2 absolute z-10"/>
        </div>

        <div class="">
            <img :src="require('@/images/conf.jpg')" class="object-cover h-96 w-full justify-center" />
        </div>

        <div class="absolute z-10 top-52 w-full flex justify-center text-white text-5xl">
            Get Familiar With Us
        </div>

        <div class="p-4"></div>

        <div class="container mx-auto">
                
            <div class="text-center text-6xl">
                About Nubia Capital. 
            </div>

            <div>
                We aim to become the most reputable private investment firm with a focus on the African continent 
            </div>

            <div>	
                With access to more than $4 billion of capital, we are conscientiously investing in Africa to help
                exceptional people create and grow exceptional
                businesses. We believe that conscientious investing is key to a better future – 
                a healthier planet, a smarter economy, a diverse and happier community, and a broader path to prosperity.
                Nubia is a people driven investment firm with a focus on the African Continent.
            </div>

            <div class="p-4"></div>

            <div class="text-center text-4xl">The Nubia Way</div>
            <div class="p-2"></div>

            <div>We win by having the best people work on the best opportunities using the very best practices. 

                CEOs and Founders are at the center of everything we do. We work with exceptional CEOs and Founders who share our
                values and passion for building enduring purpose-driven companies. We then provide these CEOs and Founders with the 
                support and capital they need to accelerate growth in their next chapter.
            </div>

            <div class="p-4"></div>

            <div class="text-center text-4xl">Where We Invest</div>
            <div class="p-2"></div>

            <div class="grid grid-cols-4 gap-6 max-w-8xl mx-auto">
                <div class="shadow-md p-4 text-center">
                    <div class="font-bold pb-3">Geography</div>
                    <div>
                        <img :src="require('@/images/africa.png')" class="mx-auto w-40 h-40" />
                    </div>
                    <div class="p-2"></div>
                    <div class="text-sm font-semibold">Africa or Africa-focused</div>
                </div>

                <div class="shadow-md p-4 text-center">
                    <div class="font-bold pb-3">Industries/Focus areas</div>
                    <div>
                        <img :src="require('@/images/software.png')" class="mx-auto w-40 h-40" />
                    </div>
                    <div class="p-2"></div>
                    <div class="text-sm font-semibold">Software, technology-enabled businesses, industry consolidation</div>
                </div>

                <div class="shadow-md p-4 text-center">
                    <div class="font-bold pb-3">Revenue</div>
                    <div>
                        <img :src="require('@/images/revenue.png')" class="mx-auto w-40 h-40" />
                    </div>
                    <div class="p-2"></div>
                    <div class="text-sm font-semibold">Greater than $5 million</div>
                </div>

                <div class="shadow-md p-4 text-center">
                    <div class="font-bold pb-3">Enterprise value</div>
                    <div>
                        <img :src="require('@/images/value.png')" class="mx-auto w-40 h-40" />
                    </div>
                    <div class="p-2"></div>
                    <div class="text-sm font-semibold">Up to $1 billion</div>
                </div>
            </div>

            <div class="p-16"></div>

            <div class="text-center text-4xl">Transaction types</div>
            <div class="p-2"></div>

            <div class="grid grid-cols-5 gap-6 max-w-7xl mx-auto text-center">
                <div class="shadow-md p-4">
                    <div>
                        <img :src="require('@/images/capital.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>
                
                    <div class="font-bold text-sm">Growth capital</div>
                </div>

                <div class="shadow-md p-4">
                    <div>
                        <img :src="require('@/images/capital.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>
                
                    <div class="font-bold text-sm">Majority recapitalization</div>
                </div>

                <div class="shadow-md p-4">
                    <div>
                        <img :src="require('@/images/capital.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>
                
                    <div class="font-bold text-sm">100% buyout</div>
                </div>

                <div class="shadow-md p-4">
                    <div>
                        <img :src="require('@/images/capital.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>
                
                    <div class="font-bold text-sm">Corporate carve-outs and businesses undergoing transitions</div>
                </div>

                <div class="shadow-md p-4">
                    <div>
                        <img :src="require('@/images/capital.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>
                
                    <div class="font-bold text-sm">Check size: Min - $5 million | Max - $1 billion</div>
                </div>
            </div>

           <div class="p-16"></div>

            <div>
            <div class="text-center text-4xl">Working with us</div>
            <div class="p-2"></div>

            <div class="grid grid-cols-3 gap-6 max-w-7xl mx-auto">

                <div class="shadow-md p-4 max-w-sm rounded-md">
                    <div>
                        <img :src="require('@/images/capital.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Patient Capital
                    </div>

                    <div>
                        We know that building a great company takes time and we work patiently with businesses to unlock value over time.
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/investor.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Lead Investors
                    </div>

                    <div>
                        We play an active role in closing and governance whenever we are co-investing with likeminded investors
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/talent.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                         World-class talent
                    </div>

                    <div>
                        Our team consist of exceptional talent that are ready to support you from the very first day and onward. 
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/closing.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        High certainty of closing
                    </div>

                    <div>
                         Once we decide that a deal fits well with us, we move with speed and certainty toward a close
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/feedback.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Prompt Feedback 
                    </div>

                    <div>
                        We are committed to being outstanding partners to our intermediaries and we strive to deliver feedback on new deals within 24 hours.
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/invest.png')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Competitive Buy-side fee 
                    </div>
                    
                    <div>
                        We offer an attractive buy-side fee and are excited to hear about opportunities that may be a great fit for Nubia
                    </div>
                </div>
            </div>


            <div class="p-4"></div>


            <div class="text-center text-4xl">Nubia Core Values</div>
            <div class="p-2"></div>

            <div class="grid grid-cols-3 gap-6 max-w-7xl mx-auto">

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/trust.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Consistency of Character 
                    </div>
                    <div>
                        We have good motives, we keep our word and we choose the right path – even when it’s difficult.
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/climb.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Continuous improvement 
                    </div>
                    <div>
                        We always work in a continuum of learning and implementation. Knowing that things can always be better.
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/steward.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Stewardship
                    </div>
                    <div>
                        We treat every resource in our care like it is truly ours.
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/done.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Get it done 
                    </div>

                    <div>
                        We know that time is the most valuable resource on the planet, so we strive to always be at the
                        right place at the right time doing the right things.
                    </div>
                </div>

                <div class="shadow-md p-4 rounded-md">
                    <div>
                        <img :src="require('@/images/grit.svg')" class="mx-auto w-60 h-48" />
                    </div>
                    <div class="p-2"></div>

                    <div class="font-bold text-center">
                        Grit 
                    </div>

                    <div>
                        We combine perseverance, tenacity, and passion in our quest to fulfil our mission.
                    </div>
                </div>
            </div>
            </div>

            <div class="p-4"></div>
        </div>

       
    </div>
</template>

<script>
export default {
    name: 'IndexPage'
}
</script>

<style>

</style>