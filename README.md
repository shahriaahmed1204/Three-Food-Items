<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .menu-container {
            max-width: 1000px;
            margin: 0 auto;
        }
        .category-title {
            color: #d9534f;
            border-bottom: 2px solid #d9534f;
            padding-bottom: 5px;
            margin-top: 40px;
            font-size: 1.8rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }
        .food-card {
            background: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            border: 1px solid #eee;
        }
        .food-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 10px;
        }
        .food-name {
            font-size: 1.3rem;
            font-weight: bold;
            color: #222;
            margin: 0;
        }
        .food-price {
            font-size: 1.2rem;
            color: #27ae60;
            font-weight: bold;
        }
        .food-description {
            font-size: 0.95rem;
            color: #666;
            line-height: 1.5;
            margin: 0 0 15px 0;
            flex-grow: 1;
        }
        .payment-placeholder {
            margin-top: auto;
        }
        /* Style for your existing payment buttons can go here */
        .order-btn {
            background-color: #27ae60;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="menu-container">

    <!-- SIGNATURE DISHES CATEGORY (2 Items) -->
    <h2 class="category-title">Signature Dishes</h2>
    <div class="grid-container">
        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Chef's Truffle Glazed Ribeye</h3>
                    <span class="food-price">$42.00</span>
                </div>
                <p class="food-description">A premium, 21-day aged ribeye steak grilled to perfection, brushed with our house-made black truffle reduction, and served with charred asparagus.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>

        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Pan-Seared Herb Chilean Seabass</h3>
                    <span class="food-price">$38.50</span>
                </div>
                <p class="food-description">Wild-caught Chilean seabass pan-seared until crisp, resting on a bed of creamy saffron risotto and drizzled with a citrus-herb butter infusion.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>
    </div>


    <!-- REGIONAL DISHES CATEGORY (4 Items) -->
    <h2 class="category-title">Regional Dishes</h2>
    <div class="grid-container">
        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Traditional Kacchi Biryani</h3>
                    <span class="food-price">$18.99</span>
                </div>
                <p class="food-description">An authentic regional classic featuring tender raw mutton layered with fragrant basmati rice, potatoes, and a blend of aromatic spices, slow-cooked to perfection.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>

        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Tuscan Garlic Chicken Pasta</h3>
                    <span class="food-price">$16.50</span>
                </div>
                <p class="food-description">A rustic regional Italian favorite. Juicy grilled chicken strips tossed with fettuccine, sun-dried tomatoes, and fresh spinach in a rich garlic cream sauce.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>

        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Oaxacan Mole Poblano</h3>
                    <span class="food-price">$19.00</span>
                </div>
                <p class="food-description">Tender braised chicken thigh smothered in a complex, traditional Mexican dark mole sauce crafted from rich chiles, spices, and a hint of Mexican chocolate.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>

        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Louisiana Seafood Gumbo</h3>
                    <span class="food-price">$17.50</span>
                </div>
                <p class="food-description">A deeply flavorful southern staple packed with fresh shrimp, crabmeat, and spicy andouille sausage, slow-simmered in a dark, traditional roux base over rice.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>
    </div>


    <!-- DESSERT CATEGORIES (3 Items) -->
    <h2 class="category-title">Desserts</h2>
    <div class="grid-container">
        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Molten Lava Chocolate Cake</h3>
                    <span class="food-price">$8.50</span>
                </div>
                <p class="food-description">A rich, decadent chocolate cake baked fresh with a deeply fudgy, warm molten center. Served with a side of premium vanilla bean ice cream.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>

        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Classic Madagascar Crème Brûlée</h3>
                    <span class="food-price">$9.00</span>
                </div>
                <p class="food-description">A silky, smooth vanilla bean custard base topped with a layer of hardened, perfectly torched caramelized sugar crackle.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>

        <div class="food-card">
            <div>
                <div class="food-header">
                    <h3 class="food-name">Traditional Saffron Rasmalai</h3>
                    <span class="food-price">$7.50</span>
                </div>
                <p class="food-description">Soft, flattened cottage cheese patties soaked in a rich, sweet condensed milk syrup flavored beautifully with crushed saffron threads and pistachios.</p>
            </div>
            <div class="payment-placeholder">
                <!-- Insert your existing payment connection/button code here -->
                <button class="order-btn">Add to Cart</button>
            </div>
        </div>
    </div>

</div>

</body>
</html>
