<script setup>
import { ref } from 'vue'

const inputValue = ref('')
</script>

<template>
    <v-container fluid class="pa-0">

        <!-- Hero carousel: original image paths retained -->
        <v-container max-width="100%">
            <v-row>
                <v-col>
                    <v-carousel cycle hide-delimiters>
                        <v-carousel-item src="/jewellery images/carousel1.jpg" cover>
                            <div class="d-flex flex-column justify-center fill-height px-8 px-md-16">
                                <h1 class="text-h3 text-white font-weight-bold">Timeless Pieces, Made for You</h1>
                                <p class="text-h6 text-white mt-3 mb-6">
                                    Discover elegant jewellery designed to add a little sparkle to every moment.
                                </p>
                                <div>
                                    <v-btn color="primary" size="large" rounded="pill" class="mr-3">Shop Now</v-btn>
                                    <v-btn color="white" variant="outlined" size="large" rounded="pill">Explore Jewellery</v-btn>
                                </div>
                            </div>
                        </v-carousel-item>

                        <v-carousel-item src="/jewellery images/carousel2.jpg" cover>
                            <div class="d-flex flex-column justify-center fill-height px-8 px-md-16">
                                <h2 class="text-h3 text-white font-weight-bold">A Little Sparkle, Every Day</h2>
                                <p class="text-h6 text-white mt-3">Find jewellery for every moment.</p>
                            </div>
                        </v-carousel-item>

                        <v-carousel-item src="/jewellery images/carousel3.jpg" cover>
                            <div class="d-flex flex-column justify-center fill-height px-8 px-md-16">
                                <h2 class="text-h3 text-white font-weight-bold">Make It Your Statement</h2>
                                <p class="text-h6 text-white mt-3">Discover pieces that reflect your style.</p>
                            </div>
                        </v-carousel-item>

                        <v-carousel-item src="/jewellery images/carousel4.jpg" cover>
                            <div class="d-flex flex-column justify-center fill-height px-8 px-md-16">
                                <h2 class="text-h3 text-white font-weight-bold">Little Luxuries, Big Moments</h2>
                                <p class="text-h6 text-white mt-3">A special touch for everyday style.</p>
                            </div>
                        </v-carousel-item>
                    </v-carousel>
                </v-col>
            </v-row>
        </v-container>

        <!-- Shopping benefits -->
        <v-container max-width="100%">
            <v-row>
                <v-col cols="6" md="3" class="text-center">
                    <v-avatar color="primary" variant="tonal" size="64"><v-icon size="32">mdi-truck-delivery-outline</v-icon></v-avatar>
                    <h3 class="text-subtitle-1 font-weight-bold mt-2">Fast Delivery</h3>
                    <p class="text-caption">Straight to your door</p>
                </v-col>
                <v-col cols="6" md="3" class="text-center">
                    <v-avatar color="primary" variant="tonal" size="64"><v-icon size="32">mdi-check-decagram-outline</v-icon></v-avatar>
                    <h3 class="text-subtitle-1 font-weight-bold mt-2">Quality Jewellery</h3>
                    <p class="text-caption">Carefully picked for you</p>
                </v-col>
                <v-col cols="6" md="3" class="text-center">
                    <v-avatar color="primary" variant="tonal" size="64"><v-icon size="32">mdi-shield-lock-outline</v-icon></v-avatar>
                    <h3 class="text-subtitle-1 font-weight-bold mt-2">Secure Shopping</h3>
                    <p class="text-caption">Easy and safe checkout</p>
                </v-col>
                <v-col cols="6" md="3" class="text-center">
                    <v-avatar color="primary" variant="tonal" size="64"><v-icon size="32">mdi-headset</v-icon></v-avatar>
                    <h3 class="text-subtitle-1 font-weight-bold mt-2">Friendly Support</h3>
                    <p class="text-caption">Here when you need us</p>
                </v-col>
            </v-row>
        </v-container>

        <!-- About us -->
        <v-container max-width="100%">
            <v-row>
                <v-col>
                    <v-card align="center" rounded="xl" elevation="6" border class="pa-6">
                        <v-icon color="primary" size="48">mdi-diamond-stone</v-icon>
                        <v-card-title class="text-h4 font-weight-bold text-wrap">Welcome to Auriella Jewellery</v-card-title>
                        <v-divider color="primary" thickness="4" length="70" class="mx-auto my-3" />
                        <v-card-text class="text-body-large mx-auto">
                            Discover elegant jewellery designed to add a little sparkle to every moment.
                            From everyday pieces to special occasions, find something that feels uniquely you.
                        </v-card-text>
                        <v-card-text class="text-body-large mx-auto">
                            Explore our collection and find your next favourite piece. A little sparkle, a lot of personality.
                        </v-card-text>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>

        <!-- Jewellery categories: original image paths retained -->
        <v-container max-width="100%">
            <div class="text-center mb-6">
                <h2 class="text-h4 font-weight-bold">Shop by Category</h2>
                <p class="text-medium-emphasis mt-2">Find your next favourite little luxury.</p>
            </div>
            <v-row>
                <v-col cols="12" sm="6" md="3">
                    <v-card hover color="primary" rounded="xl" elevation="6" class="h-100 d-flex flex-column">
                        <v-img src="/Jewellery/carousel1.3.jpg" cover height="200"></v-img>
                        <v-card-title class="font-weight-bold"><v-icon class="mr-2">mdi-bracelet</v-icon>Bracelets</v-card-title>
                        <v-card-text>Stack it, style it, own it.</v-card-text>
                        <v-spacer></v-spacer>
                        <v-btn class="ma-4" variant="flat" rounded="pill" append-icon="mdi-arrow-right">Learn More</v-btn>
                    </v-card>
                </v-col>

                <v-col cols="12" sm="6" md="3">
                    <v-card hover color="primary" rounded="xl" elevation="6" class="h-100 d-flex flex-column">
                        <v-img src="/Jewellery/carousel 1.4.jpg" cover height="200"></v-img>
                        <v-card-title class="font-weight-bold"><v-icon class="mr-2">mdi-necklace</v-icon>Necklaces</v-card-title>
                        <v-card-text>A little sparkle around your neck, a whole lot of personality.</v-card-text>
                        <v-spacer></v-spacer>
                        <v-btn class="ma-4" variant="flat" rounded="pill" append-icon="mdi-arrow-right">Learn More</v-btn>
                    </v-card>
                </v-col>

                <v-col cols="12" sm="6" md="3">
                    <v-card hover color="primary" rounded="xl" elevation="6" class="h-100 d-flex flex-column">
                        <v-img src="/Jewellery/carousel 1.6.jpg" cover height="200"></v-img>
                        <v-card-title class="font-weight-bold"><v-icon class="mr-2">mdi-diamond-stone</v-icon>Earrings</v-card-title>
                        <v-card-text>Small detail. Big statement.</v-card-text>
                        <v-spacer></v-spacer>
                        <v-btn class="ma-4" variant="flat" rounded="pill" append-icon="mdi-arrow-right">Learn More</v-btn>
                    </v-card>
                </v-col>

                <v-col cols="12" sm="6" md="3">
                    <v-card hover color="primary" rounded="xl" elevation="6" class="h-100 d-flex flex-column">
                        <v-img src="/Jewellery/carousel 1.1.jpg" cover height="200"></v-img>
                        <v-card-title class="font-weight-bold"><v-icon class="mr-2">mdi-gift-outline</v-icon>More Little Luxuries</v-card-title>
                        <v-card-text>More little luxuries, more reasons to shine.</v-card-text>
                        <v-spacer></v-spacer>
                        <v-btn class="ma-4" variant="flat" rounded="pill" append-icon="mdi-arrow-right">Learn More</v-btn>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>

        <!-- Footer -->
        <v-container max-width="100%" class="mt-6 bg-secondary">
            <v-row>
                <v-col cols="12" md="4">
                    <v-card height="300px" color="secondary" flat>
                        <v-card-title class="font-weight-bold">Subscribe to our mailing list</v-card-title>
                        <v-card-text>See it. Love it. Inbox it. Your little luxury awaits.</v-card-text>
                        <v-text-field v-model="inputValue" label="Email address" type="email" variant="outlined" class="ma-4">
                            <template v-slot:append-inner>
                                <v-btn color="primary">Subscribe</v-btn>
                            </template>
                        </v-text-field>
                        <div class="text-center mb-4">
                            <p>Follow us on:</p>
                            <v-icon icon="mdi-instagram" size="28" class="mx-2"></v-icon>
                            <v-icon icon="mdi-twitter" size="28" class="mx-2"></v-icon>
                            <v-icon icon="mdi-facebook" size="28" class="mx-2"></v-icon>
                            <v-icon icon="mdi-tiktok" size="28" class="mx-2"></v-icon>
                        </div>
                    </v-card>
                </v-col>

                <v-col cols="12" md="4">
                    <v-card height="300px" color="secondary" flat>
                        <v-card-title class="font-weight-bold">Contact Information</v-card-title>
                        <v-card-text>
                            <p class="mb-2"><v-icon icon="mdi-map-marker-radius-outline"></v-icon> Auriella Jewellery Shop</p>
                            <p class="mb-2">132, Main Street, Nairobi</p>
                            <p class="mb-2"><v-icon icon="mdi-phone-outline"></v-icon> +254 713 258 9213</p>
                            <p><v-icon icon="mdi-email-outline"></v-icon> info@auriellajewellery.com</p>
                        </v-card-text>
                    </v-card>
                </v-col>

                <v-col cols="12" md="4">
                    <v-card height="300px" color="secondary" flat>
                        <v-card-title class="font-weight-bold">Quick Links</v-card-title>
                        <v-card-title><v-icon icon="mdi-chevron-right" color="primary"></v-icon>About Us</v-card-title>
                        <v-card-title><v-icon icon="mdi-chevron-right" color="primary"></v-icon>New Arrivals</v-card-title>
                        <v-card-title><v-icon icon="mdi-chevron-right" color="primary"></v-icon>Shipping and Delivery</v-card-title>
                        <v-card-title><v-icon icon="mdi-chevron-right" color="primary"></v-icon>News and Events</v-card-title>
                    </v-card>
                </v-col>
            </v-row>
            <v-divider class="mb-4"></v-divider>
            <p class="text-center pb-4 mb-0">© Auriella Jewellery. All rights reserved.</p>
        </v-container>
    </v-container>
</template>
