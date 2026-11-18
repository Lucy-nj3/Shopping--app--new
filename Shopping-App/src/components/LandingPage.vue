<script setup>

</script>

<template>
    <v-container max-width="100%">
        <v-row>
            <v-col>
                <v-carousel cycle hide-delimiters>
                    <v-carousel-item src="/jewellery images/carousel 8.jpg"cover></v-carousel-item>
                     <v-carousel-item src="/jewellery images/carousel 3.jpg"cover></v-carousel-item>
                      <v-carousel-item src="/jewellery images/carousel 6.jpg"cover></v-carousel-item>
                       <v-carousel-item src="/jewellery images/carousel 4.jpg"cover></v-carousel-item>
                </v-carousel>
            </v-col>
        </v-row>
    </v-container>

    <!-- About Us -->
    <v-container max-width="100%">
        <v-row>
            <v-col>
                <v-card align="center">
                <v-card-title>Welcome to the Aurelia jewellery</v-card-title>
                <v-card-text class="text-body-large">Discover elegant jewellery designed to add a little sparkle to every moment. From everyday pieces to special occasions, find something that feels uniquely you.</v-card-text>
                <v-card-text class="text-body-large">A little sparkle,a lot of personality</v-card-text>
                </v-card>
            </v-col>
        </v-row>
    </v-container>

    <!-- bracelets-->
     <v-container max-width="100%">
        <v-row>
            <v-col md="3">
                <v-card width="300px"color="primary">
                    <v-img src="/Jewellery2/carousel 1.6.jpg"cover height="200px"></v-img>
                    <v-card-title>Bracelets</v-card-title>
                    <v-card-text>stack it ,style it ,own it</v-card-text>
                    <v-btn class="ma-4">Learn More</v-btn>
                </v-card>
            </v-col>

            <v-col md="3">
                <v-card width="300px"color="primary">
                    <v-img src="/Jewellery2/carousel1.2.jpg"cover height="200px"></v-img>
                    <v-card-title>Necklaces</v-card-title>
                    <v-card-text>A little sparkle around your neck , a whole lot of personality</v-card-text>
                    <v-btn class="ma-4">Learn More</v-btn>
                </v-card>
            </v-col>

            <v-col md="3">
                <v-card width="300px"color="primary">
                    <v-img src="/Jewellery2/carousel 1.3.jpg"cover height="200px"></v-img>
                    <v-card-title>Earrrings</v-card-title>
                    <v-card-text>Small detail. Big statement</v-card-text>
                    <v-btn class="ma-4">Learn More</v-btn>
                </v-card>
            </v-col>

            <v-col md="3">
                <v-card width="300px"color="primary">
                    <v-img src="/Jewellery2/carousel1.1.jpg"cover height="200px"></v-img>
                    <v-card-title>More Little Luxuries</v-card-title>
                    <v-card-text>More Little luxuries ,More reason to shine</v-card-text>
                    <v-btn class="ma-4">Learn More</v-btn>
                </v-card>
            </v-col>
        </v-row>
     </v-container>

     <!-- Footer -->
      <v-container max-width="100%" class="mt-6 bg-secondary">
        <v-row> 
            <v-col md="4">
                <v-card height="300px"color="secondary" flat>
                    <v-card-title>subscribe to our mailing list</v-card-title>
                    <v-card-text>See it.Love it.Inbox it. Your Little Luxury awaits</v-card-text>
                    <v-text-field v-model="inputvalue" label="Email address"outlined class="ma-4">
                        <template v-slot:append-inner>
                        <v-btn color="primary">subscribe </v-btn>
                        </template>
                    </v-text-field>
                    <div class="text-center mb-4">
                        <p>Follow us on:</p>
                        <v-icon icon="mdi-instagram"></v-icon>
                        <v-icon icon="mdi-twitter"></v-icon>
                        <v-icon icon="mdi-facebook"></v-icon>
                        <v-icon icon="mdi-tiktok"></v-icon>

                    </div>
                </v-card>
            </v-col>
            <v-col md="4">
                <v-card height="300px"color="secondary"flat>
                    <v-card-title>Contact Information</v-card-title>
                    <v-card-text>
                        <p>
                            <v-icon icon="mdi-map-marker-radius-outline"></v-icon>
                            Auriela jewellery shop
                        </p>
                        <p>132,main street, Nairobi</P>
                            <p>2547132589213</p>
                        <P>
                            <v-icon icon="mdi-email-outline"></v-icon>
                            info@theaurielajewellery.commitment
                        </p>
                    </v-card-text>
                </v-card>
            </v-col>
            <v-col>
                <v-card height="300px"color="secondary"flat>
                    <v-card-title>Quick Links</v-card-title>
                    <v-card-text>About Us</v-card-text>
                    <v-card-text>New Arrivals</v-card-text>
                    <v-card-text>Shipping and Delivery</v-card-text>
                    <v-card-text>News and Events</v-card-text>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
    </template>