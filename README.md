<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سوپرمارکت VIP | خرید آنلاین با تجربه‌ای منحصر به فرد</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <style>
        :root {
            --primary-color: #00a651;
            --secondary-color: #ff5722;
            --accent-color: #ffc107;
            --dark-color: #263238;
            --light-color: #f5f5f5;
            --success-color: #4caf50;
            --danger-color: #f44336;
            --warning-color: #ff9800;
            --info-color: #2196f3;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Vazir', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        @font-face {
            font-family: 'Vazir';
            src: url('https://cdn.jsdelivr.net/gh/rastikerdar/vazir-font@v30.1.0/dist/Vazir.woff2') format('woff2');
            font-weight: normal;
            font-style: normal;
        }
        
        body {
            background-color: var(--light-color);
            color: var(--dark-color);
            overflow-x: hidden;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary-color), #007944);
            color: white;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
            z-index: 10;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path fill="rgba(255,255,255,0.05)" d="M0,0 L100,0 L100,100 L0,100 Z" /></svg>');
            background-size: cover;
            z-index: -1;
        }
        
        .logo {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        
        .logo:hover {
            transform: scale(1.05);
        }
        
        .logo i {
            margin-left: 0.5rem;
            color: var(--accent-color);
        }
        
        .header-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
        }
        
        .user-actions a {
            color: white;
            margin-left: 1rem;
            text-decoration: none;
            transition: color 0.3s;
            font-size: 0.9rem;
            cursor: pointer;
        }
        
        .user-actions a:hover {
            color: var(--accent-color);
        }
        
        .search-bar {
            margin: 1rem auto;
            display: flex;
            max-width: 600px;
            position: relative;
            z-index: 5;
        }
        
        .search-bar input {
            flex: 1;
            padding: 0.8rem 1.2rem;
            border: none;
            border-radius: 30px 0 0 30px;
            font-size: 1rem;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            transition: all 0.3s;
        }
        
        .search-bar input:focus {
            outline: none;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.2);
        }
        
        .search-bar button {
            padding: 0 1.5rem;
            background: linear-gradient(to right, var(--secondary-color), #e64a19);
            color: white;
            border: none;
            border-radius: 0 30px 30px 0;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .search-bar button:hover {
            background: linear-gradient(to right, #e64a19, #d84315);
            transform: translateX(-2px);
        }
        
        /* Navigation */
        nav {
            background-color: white;
            padding: 0.5rem;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        nav ul li {
            margin: 0 0.5rem;
            position: relative;
        }
        
        nav ul li::after {
            content: '';
            position: absolute;
            bottom: 0;
            right: 0;
            width: 0;
            height: 2px;
            background-color: var(--primary-color);
            transition: width 0.3s ease;
        }
        
        nav ul li:hover::after {
            width: 100%;
            left: 0;
        }
        
        nav ul li a {
            color: var(--dark-color);
            text-decoration: none;
            padding: 0.5rem 1rem;
            display: block;
            font-weight: 500;
            transition: all 0.3s;
            cursor: pointer;
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        nav ul li a i {
            margin-left: 0.5rem;
        }
        
        /* Main Container */
        .container {
            display: flex;
            padding: 1rem;
            max-width: 1400px;
            margin: 0 auto;
            transition: all 0.3s;
        }
        
        /* Sidebar */
        .sidebar {
            width: 280px;
            background-color: white;
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            margin-left: 1rem;
            position: sticky;
            top: 80px;
            height: fit-content;
            transition: all 0.3s;
        }
        
        .sidebar:hover {
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.12);
        }
        
        .sidebar h3 {
            margin-bottom: 1.5rem;
            color: var(--primary-color);
            border-bottom: 2px dashed #eee;
            padding-bottom: 0.8rem;
            font-size: 1.2rem;
            display: flex;
            align-items: center;
        }
        
        .sidebar h3 i {
            margin-left: 0.5rem;
        }
        
        .sidebar ul {
            list-style: none;
        }
        
        .sidebar ul li {
            margin-bottom: 0.8rem;
            position: relative;
            overflow: hidden;
        }
        
        .sidebar ul li::before {
            content: '';
            position: absolute;
            right: -10px;
            top: 50%;
            transform: translateY(-50%);
            width: 5px;
            height: 5px;
            background-color: var(--primary-color);
            border-radius: 50%;
            opacity: 0;
            transition: all 0.3s;
        }
        
        .sidebar ul li:hover::before {
            right: 0;
            opacity: 1;
        }
        
        .sidebar ul li a {
            color: #555;
            text-decoration: none;
            display: block;
            padding: 0.5rem 0.8rem;
            border-radius: 6px;
            transition: all 0.3s;
            position: relative;
            display: flex;
            align-items: center;
            cursor: pointer;
        }
        
        .sidebar ul li a:hover {
            background-color: rgba(0, 166, 81, 0.1);
            color: var(--primary-color);
            transform: translateX(-5px);
        }
        
        .sidebar ul li a i {
            margin-left: 0.8rem;
            width: 20px;
            text-align: center;
        }
        
        .sidebar ul li a .badge {
            margin-right: auto;
            background-color: var(--accent-color);
            color: var(--dark-color);
            padding: 0.2rem 0.5rem;
            border-radius: 12px;
            font-size: 0.7rem;
            font-weight: bold;
        }
        
        /* Price Filter */
        .price-filter {
            margin-top: 1.5rem;
        }
        
        .price-range {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.5rem;
            color: #666;
            font-size: 0.9rem;
        }
        
        .range-slider {
            width: 100%;
            height: 5px;
            background-color: #ddd;
            border-radius: 5px;
            margin-top: 1rem;
            position: relative;
        }
        
        .range-slider .progress {
            height: 100%;
            left: 0;
            right: 0;
            position: absolute;
            border-radius: 5px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
        }
        
        .range-input {
            position: relative;
        }
        
        .range-input input {
            position: absolute;
            width: 100%;
            height: 5px;
            top: -5px;
            background: none;
            pointer-events: none;
            -webkit-appearance: none;
            -moz-appearance: none;
        }
        
        input[type="range"]::-webkit-slider-thumb {
            height: 17px;
            width: 17px;
            border-radius: 50%;
            background: var(--primary-color);
            pointer-events: auto;
            -webkit-appearance: none;
            box-shadow: 0 0 6px rgba(0, 0, 0, 0.2);
            cursor: pointer;
            transition: all 0.2s;
        }
        
        input[type="range"]::-webkit-slider-thumb:hover {
            transform: scale(1.2);
            background: var(--secondary-color);
        }
        
        /* Main Content */
        .main-content {
            flex: 1;
            position: relative;
        }
        
        /* Banner */
        .banner {
            background: linear-gradient(135deg, rgba(0, 166, 81, 0.9), rgba(0, 121, 107, 0.9));
            color: white;
            padding: 2rem;
            border-radius: 12px;
            margin-bottom: 2rem;
            position: relative;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease;
        }
        
        .banner::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path fill="rgba(255,255,255,0.05)" d="M0,0 L100,0 L100,100 L0,100 Z" /></svg>');
            background-size: cover;
            z-index: 1;
        }
        
        .banner-content {
            position: relative;
            z-index: 2;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .banner-text h2 {
            font-size: 1.8rem;
            margin-bottom: 0.5rem;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        
        .banner-text p {
            font-size: 1rem;
            margin-bottom: 1rem;
            opacity: 0.9;
        }
        
        .banner-btn {
            background-color: white;
            color: var(--primary-color);
            border: none;
            padding: 0.8rem 1.5rem;
            border-radius: 30px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        
        .banner-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        
        .banner-image img {
            width: 200px;
            animation: float 3s ease-in-out infinite;
        }
        
        /* Products Grid */
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            gap: 1.5rem;
            margin-bottom: 3rem;
        }
        
        .product-card {
            background-color: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: all 0.3s;
            position: relative;
            animation: fadeInUp 0.5s ease;
        }
        
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .product-badge {
            position: absolute;
            top: 10px;
            left: 10px;
            background-color: var(--danger-color);
            color: white;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
            z-index: 2;
            animation: pulse 2s infinite;
        }
        
        .product-image {
            height: 200px;
            overflow: hidden;
            position: relative;
        }
        
        .product-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .product-card:hover .product-image img {
            transform: scale(1.1);
        }
        
        .product-info {
            padding: 1.2rem;
            position: relative;
        }
        
        .product-title {
            font-weight: bold;
            margin-bottom: 0.5rem;
            font-size: 1rem;
            color: var(--dark-color);
            transition: color 0.3s;
        }
        
        .product-card:hover .product-title {
            color: var(--primary-color);
        }
        
        .product-category {
            display: inline-block;
            background-color: rgba(0, 166, 81, 0.1);
            color: var(--primary-color);
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-size: 0.7rem;
            margin-bottom: 0.5rem;
        }
        
        .product-rating {
            display: flex;
            align-items: center;
            margin-bottom: 0.5rem;
        }
        
        .product-rating .stars {
            color: var(--warning-color);
            margin-left: 0.3rem;
        }
        
        .product-rating .count {
            font-size: 0.8rem;
            color: #777;
        }
        
        .product-price {
            display: flex;
            align-items: center;
            margin-bottom: 0.8rem;
        }
        
        .current-price {
            color: var(--danger-color);
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        .original-price {
            text-decoration: line-through;
            color: #999;
            font-size: 0.9rem;
            margin-right: 0.5rem;
        }
        
        .discount {
            background-color: var(--accent-color);
            color: var(--dark-color);
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-size: 0.7rem;
            font-weight: bold;
            margin-right: auto;
        }
        
        .product-actions {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-top: 0.8rem;
            border-top: 1px dashed #eee;
        }
        
        .add-to-cart {
            background: linear-gradient(to right, var(--primary-color), #008c4a);
            color: white;
            border: none;
            padding: 0.6rem 1.2rem;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            font-weight: 500;
        }
        
        .add-to-cart:hover {
            background: linear-gradient(to right, #008c4a, #007944);
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 166, 81, 0.3);
        }
        
        .add-to-cart i {
            margin-left: 0.5rem;
        }
        
        .action-buttons {
            display: flex;
        }
        
        .wishlist, .compare, .quick-view {
            width: 36px;
            height: 36px;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            background-color: #f5f5f5;
            color: #777;
            margin-right: 0.5rem;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .wishlist:hover, .compare:hover, .quick-view:hover {
            background-color: var(--primary-color);
            color: white;
            transform: translateY(-2px);
        }
        
        .wishlist.active {
            background-color: var(--danger-color);
            color: white;
        }
        
        /* Category Title */
        .category-title {
            margin: 2rem 0 1.5rem;
            color: var(--primary-color);
            border-bottom: 2px solid #eee;
            padding-bottom: 0.8rem;
            font-size: 1.5rem;
            display: flex;
            align-items: center;
        }
        
        .category-title i {
            margin-left: 0.8rem;
            color: var(--secondary-color);
        }
        
        /* Cart Icon */
        .cart-icon {
            position: fixed;
            bottom: 2rem;
            left: 2rem;
            background: linear-gradient(135deg, var(--primary-color), #008c4a);
            color: white;
            width: 70px;
            height: 70px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.8rem;
            cursor: pointer;
            box-shadow: 0 5px 20px rgba(0, 166, 81, 0.4);
            z-index: 100;
            transition: all 0.3s;
            animation: bounce 2s infinite;
        }
        
        .cart-icon:hover {
            transform: scale(1.1) translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 166, 81, 0.5);
        }
        
        .cart-count {
            position: absolute;
            top: -5px;
            right: -5px;
            background-color: var(--danger-color);
            color: white;
            width: 28px;
            height: 28px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 0.9rem;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            transition: all 0.3s;
        }
        
        .cart-icon:hover .cart-count {
            transform: scale(1.1);
        }
        
        /* Cart Modal */
        .cart-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            transition: opacity 0.3s;
        }
        
        .cart-modal.active {
            display: flex;
            opacity: 1;
            animation: fadeIn 0.3s ease;
        }
        
        .cart-content {
            background-color: white;
            width: 90%;
            max-width: 900px;
            max-height: 90vh;
            border-radius: 12px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            transform: translateY(20px);
            transition: transform 0.3s;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        
        .cart-modal.active .cart-content {
            transform: translateY(0);
        }
        
        .cart-header {
            background: linear-gradient(135deg, var(--primary-color), #008c4a);
            color: white;
            padding: 1.2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .cart-header h3 {
            font-size: 1.3rem;
            display: flex;
            align-items: center;
        }
        
        .cart-header h3 i {
            margin-left: 0.8rem;
        }
        
        .close-cart {
            background: none;
            border: none;
            color: white;
            font-size: 1.8rem;
            cursor: pointer;
            transition: transform 0.3s;
        }
        
        .close-cart:hover {
            transform: rotate(90deg);
        }
        
        .cart-items {
            flex: 1;
            overflow-y: auto;
            padding: 1.5rem;
        }
        
        .cart-item {
            display: flex;
            margin-bottom: 1.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid #eee;
            animation: fadeIn 0.5s ease;
            position: relative;
        }
        
        .cart-item-remove {
            position: absolute;
            top: 0;
            left: 0;
            background: none;
            border: none;
            color: #999;
            font-size: 1.2rem;
            cursor: pointer;
            transition: color 0.3s;
        }
        
        .cart-item-remove:hover {
            color: var(--danger-color);
        }
        
        .cart-item-image {
            width: 100px;
            height: 100px;
            overflow: hidden;
            margin-left: 1.5rem;
            border-radius: 8px;
            flex-shrink: 0;
        }
        
        .cart-item-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s;
        }
        
        .cart-item:hover .cart-item-image img {
            transform: scale(1.05);
        }
        
        .cart-item-details {
            flex: 1;
        }
        
        .cart-item-title {
            font-weight: bold;
            margin-bottom: 0.5rem;
            font-size: 1.1rem;
            color: var(--dark-color);
        }
        
        .cart-item-price {
            color: var(--danger-color);
            font-weight: bold;
            margin-bottom: 0.5rem;
            display: block;
        }
        
        .cart-item-actions {
            display: flex;
            align-items: center;
            margin-top: 0.8rem;
        }
        
        .quantity-control {
            display: flex;
            align-items: center;
            margin-left: 1rem;
            border: 1px solid #ddd;
            border-radius: 6px;
            overflow: hidden;
        }
        
        .quantity-btn {
            width: 35px;
            height: 35px;
            background-color: #f9f9f9;
            border: none;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.1rem;
            transition: all 0.3s;
        }
        
        .quantity-btn:hover {
            background-color: #eee;
        }
        
        .quantity-btn.decrease {
            color: var(--danger-color);
        }
        
        .quantity-btn.increase {
            color: var(--success-color);
        }
        
        .quantity {
            margin: 0 0.5rem;
            width: 40px;
            text-align: center;
            font-weight: bold;
        }
        
        .cart-footer {
            padding: 1.5rem;
            background-color: #f9f9f9;
            border-top: 1px solid #eee;
        }
        
        .cart-summary {
            margin-bottom: 1.5rem;
        }
        
        .summary-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.8rem;
            color: #555;
        }
        
        .cart-total {
            display: flex;
            justify-content: space-between;
            margin-bottom: 1.5rem;
            font-weight: bold;
            font-size: 1.3rem;
            color: var(--dark-color);
            padding-top: 0.8rem;
            border-top: 1px dashed #ccc;
        }
        
        .checkout-btn {
            width: 100%;
            padding: 1rem;
            background: linear-gradient(to right, var(--primary-color), #008c4a);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 10px rgba(0, 166, 81, 0.3);
        }
        
        .checkout-btn:hover {
            background: linear-gradient(to right, #008c4a, #007944);
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(0, 166, 81, 0.4);
        }
        
        .checkout-btn i {
            margin-left: 0.8rem;
        }
        
        .empty-cart {
            text-align: center;
            padding: 3rem;
            color: #888;
            animation: fadeIn 0.5s ease;
        }
        
        .empty-cart i {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: #ddd;
        }
        
        .empty-cart p {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }
        
        .continue-shopping {
            background-color: #f0f0f0;
            color: #555;
            border: none;
            padding: 0.8rem 1.5rem;
            border-radius: 6px;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .continue-shopping:hover {
            background-color: #e0e0e0;
            transform: translateY(-2px);
        }
        
        /* Quick View Modal */
        .quick-view-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            transition: opacity 0.3s;
        }
        
        .quick-view-modal.active {
            display: flex;
            opacity: 1;
        }
        
        .quick-view-content {
            background-color: white;
            width: 90%;
            max-width: 1000px;
            max-height: 90vh;
            border-radius: 12px;
            overflow: hidden;
            display: flex;
            transform: translateY(20px);
            transition: transform 0.3s;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        
        .quick-view-modal.active .quick-view-content {
            transform: translateY(0);
        }
        
        .quick-view-image {
            flex: 1;
            min-height: 500px;
            background-color: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem;
        }
        
        .quick-view-image img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
            transition: transform 0.3s;
        }
        
        .quick-view-image img:hover {
            transform: scale(1.05);
        }
        
        .quick-view-details {
            flex: 1;
            padding: 2rem;
            overflow-y: auto;
        }
        
        .close-quick-view {
            position: absolute;
            top: 1rem;
            left: 1rem;
            background: none;
            border: none;
            color: #999;
            font-size: 1.8rem;
            cursor: pointer;
            transition: all 0.3s;
            z-index: 2;
        }
        
        .close-quick-view:hover {
            color: var(--danger-color);
            transform: rotate(90deg);
        }
        
        .quick-view-title {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            color: var(--dark-color);
        }
        
        .quick-view-price {
            font-size: 1.5rem;
            color: var(--danger-color);
            font-weight: bold;
            margin-bottom: 1rem;
        }
        
        .quick-view-description {
            color: #666;
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }
        
        .quick-view-actions {
            display: flex;
            margin-top: 2rem;
        }
        
        .add-to-cart-lg {
            background: linear-gradient(to right, var(--primary-color), #008c4a);
            color: white;
            border: none;
            padding: 0.8rem 1.8rem;
            border-radius: 6px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            margin-left: 1rem;
        }
        
        .add-to-cart-lg:hover {
            background: linear-gradient(to right, #008c4a, #007944);
            transform: translateY(-2px);
            box-shadow: 0 4px 10px rgba(0, 166, 81, 0.3);
        }
        
        .add-to-cart-lg i {
            margin-left: 0.8rem;
        }
        
        .add-to-wishlist {
            background-color: #f5f5f5;
            color: #777;
            border: none;
            padding: 0.8rem 1.5rem;
            border-radius: 6px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
        }
        
        .add-to-wishlist:hover {
            background-color: #e0e0e0;
            transform: translateY(-2px);
        }
        
        .add-to-wishlist i {
            margin-left: 0.8rem;
        }
        
        /* Login/Signup Modal */
        .auth-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            transition: opacity 0.3s;
        }
        
        .auth-modal.active {
            display: flex;
            opacity: 1;
        }
        
        .auth-content {
            background-color: white;
            width: 90%;
            max-width: 500px;
            border-radius: 12px;
            overflow: hidden;
            transform: translateY(20px);
            transition: transform 0.3s;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        
        .auth-modal.active .auth-content {
            transform: translateY(0);
        }
        
        .auth-header {
            background: linear-gradient(135deg, var(--primary-color), #008c4a);
            color: white;
            padding: 1.2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .auth-header h3 {
            font-size: 1.3rem;
            display: flex;
            align-items: center;
        }
        
        .auth-header h3 i {
            margin-left: 0.8rem;
        }
        
        .close-auth {
            background: none;
            border: none;
            color: white;
            font-size: 1.8rem;
            cursor: pointer;
            transition: transform 0.3s;
        }
        
        .close-auth:hover {
            transform: rotate(90deg);
        }
        
        .auth-tabs {
            display: flex;
            border-bottom: 1px solid #eee;
        }
        
        .auth-tab {
            flex: 1;
            text-align: center;
            padding: 1rem;
            cursor: pointer;
            transition: all 0.3s;
            font-weight: bold;
            color: #777;
        }
        
        .auth-tab.active {
            color: var(--primary-color);
            border-bottom: 2px solid var(--primary-color);
        }
        
        .auth-form {
            padding: 2rem;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #555;
            font-weight: 500;
        }
        
        .form-group input {
            width: 100%;
            padding: 0.8rem 1rem;
            border: 1px solid #ddd;
            border-radius: 6px;
            font-size: 1rem;
            transition: all 0.3s;
        }
        
        .form-group input:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(0, 166, 81, 0.2);
        }
        
        .auth-btn {
            width: 100%;
            padding: 1rem;
            background: linear-gradient(to right, var(--primary-color), #008c4a);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            margin-top: 1rem;
        }
        
        .auth-btn:hover {
            background: linear-gradient(to right, #008c4a, #007944);
            transform: translateY(-2px);
            box-shadow: 0 4px 10px rgba(0, 166, 81, 0.3);
        }
        
        .auth-footer {
            text-align: center;
            padding: 1rem;
            border-top: 1px solid #eee;
            color: #777;
        }
        
        .auth-footer a {
            color: var(--primary-color);
            text-decoration: none;
            font-weight: bold;
        }
        
        /* About Us Page */
        .about-page, .contact-page, .support-page, .products-page {
            display: none;
            animation: fadeIn 0.5s ease;
        }
        
        .page-header {
            background: linear-gradient(135deg, rgba(0, 166, 81, 0.9), rgba(0, 121, 107, 0.9));
            color: white;
            padding: 3rem 2rem;
            margin-bottom: 2rem;
            border-radius: 12px;
            text-align: center;
        }
        
        .page-header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .page-content {
            background-color: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            line-height: 1.8;
            color: #555;
        }
        
        .page-content h2 {
            color: var(--primary-color);
            margin: 1.5rem 0 1rem;
        }
        
        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }
        
        .contact-card {
            background-color: #f9f9f9;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            transition: all 0.3s;
        }
        
        .contact-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .contact-card i {
            font-size: 2rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }
        
        .contact-card h3 {
            margin-bottom: 0.5rem;
            color: var(--dark-color);
        }
        
        /* Toast Notification */
        .toast {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            background-color: var(--success-color);
            color: white;
            padding: 1rem 1.5rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            display: flex;
            align-items: center;
            z-index: 1000;
            transform: translateY(100px);
            opacity: 0;
            transition: all 0.3s;
        }
        
        .toast.show {
            transform: translateY(0);
            opacity: 1;
        }
        
        .toast i {
            margin-left: 0.8rem;
            font-size: 1.3rem;
        }
        
        /* Loading Overlay */
        .loading-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 2000;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s;
        }
        
        .loading-overlay.active {
            opacity: 1;
            pointer-events: all;
        }
        
        .loader {
            width: 50px;
            height: 50px;
            border: 5px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top-color: white;
            animation: spin 1s ease-in-out infinite;
        }
        
        /* Responsive Styles */
        @media (max-width: 1200px) {
            .container {
                max-width: 100%;
                padding: 1rem;
            }
            
            .sidebar {
                width: 250px;
            }
        }
        
        @media (max-width: 992px) {
            .products-grid {
                grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            }
            
            .quick-view-content {
                flex-direction: column;
                max-height: 90vh;
            }
            
            .quick-view-image {
                min-height: 300px;
            }
        }
        
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
            
            .sidebar {
                width: 100%;
                margin-left: 0;
                margin-bottom: 1.5rem;
                position: static;
            }
            
            nav ul {
                justify-content: flex-start;
            }
            
            nav ul li {
                margin: 0.3rem;
            }
            
            .banner-content {
                flex-direction: column;
                text-align: center;
            }
            
            .banner-text {
                margin-bottom: 1.5rem;
            }
            
            .banner-image img {
                width: 150px;
            }
            
            .cart-content {
                width: 95%;
            }
            
            .cart-item {
                flex-direction: column;
            }
            
            .cart-item-image {
                margin-left: 0;
                margin-bottom: 1rem;
                width: 100%;
                height: 150px;
            }
            
            .cart-item-actions {
                justify-content: space-between;
            }
        }
        
        @media (max-width: 576px) {
            .products-grid {
                grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
                gap: 1rem;
            }
            
            .product-actions {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .action-buttons {
                margin-top: 0.8rem;
            }
            
            .quick-view-actions {
                flex-direction: column;
            }
            
            .add-to-cart-lg {
                margin-left: 0;
                margin-bottom: 1rem;
                width: 100%;
                justify-content: center;
            }
            
            .add-to-wishlist {
                width: 100%;
                justify-content: center;
            }
            
            .header-top {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .user-actions {
                margin-top: 0.5rem;
            }
            
            .auth-tabs {
                flex-direction: column;
            }
            
            .auth-tab {
                padding: 0.8rem;
            }
        }
        
        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }
        
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-20px); }
            60% { transform: translateY(-10px); }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
            border-radius: 10px;
        }
        
        ::-webkit-scrollbar-thumb {
            background: var(--primary-color);
            border-radius: 10px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: #008c4a;
        }
    </style>
</head>
<body>
    <!-- Loading Overlay -->
    <div class="loading-overlay" id="loading-overlay">
        <div class="loader"></div>
    </div>

    <!-- Header -->
    <header>
        <div class="header-top">
            <div class="logo animate__animated animate__fadeInDown">
                <span>سوپرمارکت VIP</span>
                <i class="fas fa-shopping-basket"></i>
            </div>
            <div class="user-actions">
                <a id="login-link"><i class="fas fa-user"></i> ورود / ثبت‌نام</a>
                <a id="support-link"><i class="fas fa-headset"></i> پشتیبانی</a>
                <a><i class="fas fa-map-marker-alt"></i> پیگیری سفارش</a>
            </div>
        </div>
        <div class="search-bar">
            <input type="text" id="search-input" placeholder="جستجوی محصولات... (مثال: شیر، برنج، نوشابه)">
            <button id="search-btn"><i class="fas fa-search"></i></button>
        </div>
    </header>
    
    <!-- Navigation -->
    <nav>
        <ul>
            <li><a id="home-link"><i class="fas fa-home"></i> خانه</a></li>
            <li><a id="discounts-link"><i class="fas fa-percentage"></i> تخفیف‌ها</a></li>
            <li><a id="best-sellers-link"><i class="fas fa-fire"></i> پرفروش‌ترین‌ها</a></li>
            <li><a id="new-arrivals-link"><i class="fas fa-bolt"></i> جدیدترین‌ها</a></li>
            <li><a id="featured-link"><i class="fas fa-gift"></i> پیشنهاد ویژه</a></li>
            <li><a id="about-link"><i class="fas fa-info-circle"></i> درباره ما</a></li>
            <li><a id="contact-link"><i class="fas fa-phone"></i> تماس با ما</a></li>
        </ul>
    </nav>
    
    <!-- Main Container -->
    <div class="container">
        <!-- Sidebar -->
        <aside class="sidebar">
            <h3><i class="fas fa-list"></i> دسته‌بندی محصولات</h3>
            <ul>
                <li><a class="category-link" data-category="لبنیات و تخم مرغ"><i class="fas fa-cheese"></i> لبنیات و تخم مرغ <span class="badge">جدید</span></a></li>
                <li><a class="category-link" data-category="نوشیدنی‌ها"><i class="fas fa-wine-bottle"></i> نوشیدنی‌ها</a></li>
                <li><a class="category-link" data-category="کالاهای اساسی"><i class="fas fa-utensils"></i> کالاهای اساسی</a></li>
                <li><a class="category-link" data-category="میوه و سبزیجات"><i class="fas fa-apple-alt"></i> میوه و سبزیجات</a></li>
                <li><a class="category-link" data-category="تنقلات"><i class="fas fa-cookie"></i> تنقلات</a></li>
                <li><a class="category-link" data-category="مواد پروتئینی"><i class="fas fa-drumstick-bite"></i> مواد پروتئینی</a></li>
                <li><a class="category-link" data-category="لوازم بهداشتی"><i class="fas fa-pump-soap"></i> لوازم بهداشتی</a></li>
                <li><a class="category-link" data-category="لوازم آشپزخانه"><i class="fas fa-blender"></i> لوازم آشپزخانه</a></li>
            </ul>
            
            <h3><i class="fas fa-filter"></i> فیلترها</h3>
            <ul>
                <li><a id="cheapest-filter"><i class="fas fa-money-bill-wave"></i> ارزان‌ترین</a></li>
                <li><a id="expensive-filter"><i class="fas fa-gem"></i> گران‌ترین</a></li>
                <li><a id="popular-filter"><i class="fas fa-eye"></i> پربازدیدترین</a></li>
                <li><a id="top-rated-filter"><i class="fas fa-star"></i> پرامتیازترین</a></li>
            </ul>
            
            <div class="price-filter">
                <h3><i class="fas fa-sliders-h"></i> محدوده قیمت</h3>
                <div class="price-range">
                    <span id="min-price">۱۰,۰۰۰ تومان</span>
                    <span id="max-price">۵۰۰,۰۰۰ تومان</span>
                </div>
                <div class="range-slider">
                    <div class="progress"></div>
                </div>
                <div class="range-input">
                    <input type="range" class="range-min" min="10000" max="500000" value="10000" step="1000">
                    <input type="range" class="range-max" min="10000" max="500000" value="500000" step="1000">
                </div>
            </div>
        </aside>
        
        <!-- Main Content -->
        <main class="main-content">
            <!-- Home Page (Default) -->
            <div id="home-page">
                <!-- Banner -->
                <div class="banner animate__animated animate__fadeIn">
                    <div class="banner-content">
                        <div class="banner-text">
                            <h2>فروش ویژه تابستانه!</h2>
                            <p>تا ۵۰٪ تخفیف برای محصولات منتخب</p>
                            <button class="banner-btn" id="view-products-btn">مشاهده محصولات <i class="fas fa-arrow-left"></i></button>
                        </div>
                        <div class="banner-image">
                            <img src="https://images.unsplash.com/photo-1606787366850-de6330128bfc?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80" alt="Summer Sale">
                        </div>
                    </div>
                </div>
                
                <!-- Featured Products -->
                <h2 class="category-title"><i class="fas fa-gift"></i> پیشنهادهای ویژه</h2>
                <div class="products-grid" id="products-container"></div>
                
                <!-- Best Sellers -->
                <h2 class="category-title"><i class="fas fa-crown"></i> پرفروش‌ترین محصولات</h2>
                <div class="products-grid" id="best-sellers-container"></div>
                
                <!-- New Arrivals -->
                <h2 class="category-title"><i class="fas fa-bolt"></i> جدیدترین محصولات</h2>
                <div class="products-grid" id="new-arrivals-container"></div>
            </div>
            
            <!-- Products Page -->
            <div id="products-page" class="products-page">
                <div class="page-header">
                    <h1>همه محصولات</h1>
                    <p>بهترین محصولات با کیفیت عالی</p>
                </div>
                <div class="products-grid" id="all-products-container"></div>
            </div>
            
            <!-- Discounts Page -->
            <div id="discounts-page" class="products-page">
                <div class="page-header">
                    <h1>تخفیف‌های ویژه</h1>
                    <p>محصولات با تخفیف برای شما</p>
                </div>
                <div class="products-grid" id="discounts-container"></div>
            </div>
            
            <!-- Best Sellers Page -->
            <div id="best-sellers-page" class="products-page">
                <div class="page-header">
                    <h1>پرفروش‌ترین محصولات</h1>
                    <p>محصولاتی که بیشترین فروش را داشته‌اند</p>
                </div>
                <div class="products-grid" id="best-sellers-page-container"></div>
            </div>
            
            <!-- New Arrivals Page -->
            <div id="new-arrivals-page" class="products-page">
                <div class="page-header">
                    <h1>جدیدترین محصولات</h1>
                    <p>تازه‌ترین محصولات اضافه شده</p>
                </div>
                <div class="products-grid" id="new-arrivals-page-container"></div>
            </div>
            
            <!-- Featured Page -->
            <div id="featured-page" class="products-page">
                <div class="page-header">
                    <h1>پیشنهادهای ویژه</h1>
                    <p>انتخاب شده‌های ما برای شما</p>
                </div>
                <div class="products-grid" id="featured-container"></div>
            </div>
            
            <!-- About Us Page -->
            <div id="about-page" class="about-page">
                <div class="page-header">
                    <h1>درباره ما</h1>
                    <p>سوپرمارکت آنلاین VIP</p>
                </div>
                <div class="page-content">
                    <h2>تاریخچه ما</h2>
                    <p>سوپرمارکت آنلاین VIP در سال ۱۴۰۰ با هدف ارائه بهترین محصولات با کیفیت عالی و قیمت مناسب تأسیس شد. ما با همکاری با بهترین تولیدکنندگان و تأمین‌کنندگان، محصولات متنوعی را برای رفاه و آسایش شما عزیزان فراهم کرده‌ایم.</p>
                    
                    <h2>چرا ما را انتخاب کنید؟</h2>
                    <p>• کیفیت بالای محصولات</p>
                    <p>• قیمت‌های مناسب و رقابتی</p>
                    <p>• تحویل سریع و به موقع</p>
                    <p>• پشتیبانی ۲۴ ساعته</p>
                    <p>• ضمانت بازگشت کالا</p>
                    
                    <h2>تیم ما</h2>
                    <p>ما تیمی متشکل از متخصصان با تجربه در زمینه فروش آنلاین هستیم که با عشق و علاقه برای خدمت به شما تلاش می‌کنیم. رضایت شما افتخار ماست.</p>
                </div>
            </div>
            
            <!-- Contact Us Page -->
            <div id="contact-page" class="contact-page">
                <div class="page-header">
                    <h1>تماس با ما</h1>
                    <p>ما اینجا هستیم تا به شما کمک کنیم</p>
                </div>
                <div class="page-content">
                    <h2>راه‌های ارتباطی</h2>
                    <p>شما می‌توانید از طریق راه‌های زیر با ما در ارتباط باشید:</p>
                    
                    <div class="contact-info">
                        <div class="contact-card">
                            <i class="fas fa-phone"></i>
                            <h3>تلفن تماس</h3>
                            <p>۰۲۱-۱۲۳۴۵۶۷۸</p>
                            <p>۰۹۱۲۳۴۵۶۷۸۹</p>
                        </div>
                        
                        <div class="contact-card">
                            <i class="fas fa-envelope"></i>
                            <h3>ایمیل</h3>
                            <p>info@vipsupermarket.ir</p>
                            <p>support@vipsupermarket.ir</p>
                        </div>
                        
                        <div class="contact-card">
                            <i class="fas fa-map-marker-alt"></i>
                            <h3>آدرس</h3>
                            <p>تهران، خیابان آزادی، پلاک ۱۲۳</p>
                        </div>
                    </div>
                    
                    <h2>ساعات کاری</h2>
                    <p>شنبه تا چهارشنبه: ۸ صبح تا ۸ شب</p>
                    <p>پنجشنبه: ۸ صبح تا ۴ بعدازظهر</p>
                </div>
            </div>
            
            <!-- Support Page -->
            <div id="support-page" class="support-page">
                <div class="page-header">
                    <h1>پشتیبانی</h1>
                    <p>ما اینجا هستیم تا به شما کمک کنیم</p>
                </div>
                <div class="page-content">
                    <h2>سوالات متداول</h2>
                    <p><strong>چگونه می‌توانم سفارشم را پیگیری کنم؟</strong></p>
                    <p>پس از ثبت سفارش، کد رهگیری برای شما ارسال می‌شود که می‌توانید از طریق بخش پیگیری سفارش در سایت وضعیت آن را بررسی کنید.</p>
                    
                    <p><strong>روش‌های پرداخت چه هستند؟</strong></p>
                    <p>شما می‌توانید از طریق درگاه پرداخت اینترنتی، کارت به کارت و یا پرداخت در محل (برای برخی مناطق) خرید خود را انجام دهید.</p>
                    
                    <p><strong>سیاست بازگشت کالا چگونه است؟</strong></p>
                    <p>در صورت عدم رضایت از کالا، تا ۷ روز پس از تحویل می‌توانید آن را مرجوع کنید. شرایط کامل در صفحه قوانین و مقررات ذکر شده است.</p>
                    
                    <h2>فرم تماس با پشتیبانی</h2>
                    <div class="form-group">
                        <label for="support-name">نام کامل</label>
                        <input type="text" id="support-name" placeholder="نام و نام خانوادگی">
                    </div>
                    <div class="form-group">
                        <label for="support-email">ایمیل</label>
                        <input type="email" id="support-email" placeholder="example@example.com">
                    </div>
                    <div class="form-group">
                        <label for="support-subject">موضوع</label>
                        <input type="text" id="support-subject" placeholder="موضوع پیام">
                    </div>
                    <div class="form-group">
                        <label for="support-message">پیام شما</label>
                        <textarea id="support-message" rows="5" placeholder="متن پیام خود را بنویسید..." style="width: 100%; padding: 0.8rem 1rem; border: 1px solid #ddd; border-radius: 6px; font-size: 1rem;"></textarea>
                    </div>
                    <button class="auth-btn">ارسال پیام</button>
                </div>
            </div>
            
            <!-- Category Products Page -->
            <div id="category-page" class="products-page">
                <div class="page-header">
                    <h1 id="category-title">دسته‌بندی محصولات</h1>
                    <p id="category-description"></p>
                </div>
                <div class="products-grid" id="category-products-container"></div>
            </div>
        </main>
    </div>
    
    <!-- Cart Icon -->
    <div class="cart-icon" id="cart-icon">
        <i class="fas fa-shopping-cart"></i>
        <span class="cart-count" id="cart-count">0</span>
    </div>
    
    <!-- Cart Modal -->
    <div class="cart-modal" id="cart-modal">
        <div class="cart-content">
            <div class="cart-header">
                <h3><i class="fas fa-shopping-cart"></i> سبد خرید شما</h3>
                <button class="close-cart" id="close-cart"><i class="fas fa-times"></i></button>
            </div>
            <div class="cart-items" id="cart-items">
                <!-- Cart items will be added dynamically with JavaScript -->
            </div>
            <div class="cart-footer">
                <div class="cart-summary">
                    <div class="summary-row">
                        <span>جمع کل اقلام:</span>
                        <span id="subtotal">۰ تومان</span>
                    </div>
                    <div class="summary-row">
                        <span>هزینه ارسال:</span>
                        <span id="shipping">۰ تومان</span>
                    </div>
                    <div class="summary-row">
                        <span>تخفیف:</span>
                        <span id="discount">۰ تومان</span>
                    </div>
                </div>
                <div class="cart-total">
                    <span>مبلغ قابل پرداخت:</span>
                    <span id="cart-total">۰ تومان</span>
                </div>
                <button class="checkout-btn"><i class="fas fa-credit-card"></i> تکمیل سفارش</button>
            </div>
        </div>
    </div>

    <!-- Quick View Modal -->
    <div class="quick-view-modal" id="quick-view-modal">
        <div class="quick-view-content">
            <button class="close-quick-view" id="close-quick-view"><i class="fas fa-times"></i></button>
            <div class="quick-view-image">
                <img src="" alt="" id="quick-view-img">
            </div>
            <div class="quick-view-details">
                <h2 class="quick-view-title" id="quick-view-title"></h2>
                <div class="product-rating">
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <span class="count">(۴۲ نظر)</span>
                </div>
                <div class="quick-view-price" id="quick-view-price"></div>
                <p class="quick-view-description">
                    این محصول با کیفیت عالی و مواد اولیه مرغوب تولید شده است. مناسب برای استفاده روزانه و حاوی تمام مواد مغذی مورد نیاز بدن می‌باشد. این محصول کاملاً بهداشتی و با مجوزهای لازم از سازمان‌های مربوطه تولید و عرضه می‌شود.
                </p>
                <div class="quick-view-actions">
                    <button class="add-to-cart-lg" id="quick-view-add-to-cart"><i class="fas fa-cart-plus"></i> افزودن به سبد خرید</button>
                    <button class="add-to-wishlist"><i class="far fa-heart"></i> افزودن به علاقه‌مندی‌ها</button>
                </div>
            </div>
        </div>
    </div>

    <!-- Login/Signup Modal -->
    <div class="auth-modal" id="auth-modal">
        <div class="auth-content">
            <div class="auth-header">
                <h3><i class="fas fa-user"></i> ورود / ثبت‌نام</h3>
                <button class="close-auth" id="close-auth"><i class="fas fa-times"></i></button>
            </div>
            <div class="auth-tabs">
                <div class="auth-tab active" id="login-tab">ورود</div>
                <div class="auth-tab" id="signup-tab">ثبت‌نام</div>
            </div>
            <div class="auth-form" id="login-form">
                <div class="form-group">
                    <label for="login-email">ایمیل</label>
                    <input type="email" id="login-email" placeholder="example@example.com">
                </div>
                <div class="form-group">
                    <label for="login-password">رمز عبور</label>
                    <input type="password" id="login-password" placeholder="رمز عبور">
                </div>
                <button class="auth-btn">ورود به حساب</button>
                <div class="auth-footer">
                    رمز عبور خود را فراموش کرده‌اید؟ <a href="#">بازیابی رمز عبور</a>
                </div>
            </div>
            <div class="auth-form" id="signup-form" style="display: none;">
                <div class="form-group">
                    <label for="signup-name">نام کامل</label>
                    <input type="text" id="signup-name" placeholder="نام و نام خانوادگی">
                </div>
                <div class="form-group">
                    <label for="signup-email">ایمیل</label>
                    <input type="email" id="signup-email" placeholder="example@example.com">
                </div>
                <div class="form-group">
                    <label for="signup-phone">شماره تلفن</label>
                    <input type="tel" id="signup-phone" placeholder="۰۹۱۲۳۴۵۶۷۸۹">
                </div>
                <div class="form-group">
                    <label for="signup-password">رمز عبور</label>
                    <input type="password" id="signup-password" placeholder="رمز عبور">
                </div>
                <div class="form-group">
                    <label for="signup-confirm-password">تکرار رمز عبور</label>
                    <input type="password" id="signup-confirm-password" placeholder="تکرار رمز عبور">
                </div>
                <button class="auth-btn">ثبت‌نام</button>
                <div class="auth-footer">
                    با ثبت‌نام، <a href="#">قوانین و مقررات</a> را می‌پذیرید
                </div>
            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div class="toast" id="toast">
        <i class="fas fa-check-circle"></i>
        <span id="toast-message">محصول به سبد خرید اضافه شد</span>
    </div>

    <script>
        // JavaScript code
        document.addEventListener('DOMContentLoaded', function() {
            // Show loading overlay
            const loadingOverlay = document.getElementById('loading-overlay');
            loadingOverlay.classList.add('active');
            
            // Hide loading overlay after 1.5 seconds (simulating data loading)
            setTimeout(() => {
                loadingOverlay.classList.remove('active');
            }, 1500);
            
            // Sample product data
            const products = [
                {
                    id: 1,
                    title: 'شیر پاستوریزه پرچرب صباح ۱ لیتری',
                    price: 45000,
                    originalPrice: 55000,
                    category: 'لبنیات و تخم مرغ',
                    image: '',
                    isNew: true,
                    isBestSeller: true,
                    isFeatured: true,
                    views: 1200,
                    rating: 4.5
                },
                {
                    id: 2,
                    title: 'نوشابه کوکاکولا ۱.۵ لیتری',
                    price: 35000,
                    originalPrice: 40000,
                    category: 'نوشیدنی‌ها',
                    image: '',
                    isBestSeller: true,
                    isFeatured: true,
                    views: 1800,
                    rating: 4.2
                },
                {
                    id: 3,
                    title: 'برنج ایرانی طارم هاشمی ۵ کیلویی',
                    price: 320000,
                    originalPrice: 350000,
                    category: 'کالاهای اساسی',
                    image: '',
                    isNew: true,
                    views: 800,
                    rating: 4.8
                },
                {
                    id: 4,
                    title: 'سیب درختی قرمز ۱ کیلویی',
                    price: 60000,
                    originalPrice: 65000,
                    category: 'میوه و سبزیجات',
                    image: '',
                    isBestSeller: true,
                    views: 1500,
                    rating: 4.6
                },
                {
                    id: 5,
                    title: 'چیپس سیب زمینی پرینگلز ۱۰۰ گرمی',
                    price: 25000,
                    originalPrice: 30000,
                    category: 'تنقلات',
                    image: '',
                    isNew: true,
                    isFeatured: true,
                    views: 900,
                    rating: 4.3
                },
                {
                    id: 6,
                    title: 'مرغ کامل تازه ۲ کیلویی',
                    price: 180000,
                    originalPrice: 200000,
                    category: 'مواد پروتئینی',
                    image: 'https://images.unsplash.com/photo-1601342630314-8427c38bf5e6?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isBestSeller: true,
                    views: 2000,
                    rating: 4.7
                },
                {
                    id: 7,
                    title: 'ماست پرچرب کاله ۹۰۰ گرمی',
                    price: 38000,
                    originalPrice: 45000,
                    category: 'لبنیات و تخم مرغ',
                    image: 'https://images.unsplash.com/photo-1542838132-92c53300491e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isNew: true,
                    views: 1100,
                    rating: 4.4
                },
                {
                    id: 8,
                    title: 'آب معدنی دماوند ۱.۵ لیتری',
                    price: 12000,
                    originalPrice: 15000,
                    category: 'نوشیدنی‌ها',
                    image: 'https://images.unsplash.com/photo-1561047029-3000c68339ca?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isBestSeller: true,
                    isFeatured: true,
                    views: 1700,
                    rating: 4.1
                },
                {
                    id: 9,
                    title: 'روغن مایع نباتی لادن ۹۰۰ میلی لیتر',
                    price: 85000,
                    originalPrice: 95000,
                    category: 'کالاهای اساسی',
                    image: 'https://images.unsplash.com/photo-1535591273668-578e31182c4f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isNew: true,
                    views: 700,
                    rating: 4.5
                },
                {
                    id: 10,
                    title: 'موز وارداتی ۱ کیلویی',
                    price: 50000,
                    originalPrice: 55000,
                    category: 'میوه و سبزیجات',
                    image: 'https://images.unsplash.com/photo-1603833665858-e61bb17a55b3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isBestSeller: true,
                    views: 1600,
                    rating: 4.6
                },
                {
                    id: 11,
                    title: 'پفک نمکی ۴۰ گرمی',
                    price: 15000,
                    originalPrice: 18000,
                    category: 'تنقلات',
                    image: 'https://images.unsplash.com/photo-1561758033-48d52648ae8b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isNew: true,
                    isFeatured: true,
                    views: 950,
                    rating: 4.0
                },
                {
                    id: 12,
                    title: 'تخم مرغ محلی ۱۰ عددی',
                    price: 75000,
                    originalPrice: 80000,
                    category: 'مواد پروتئینی',
                    image: 'https://images.unsplash.com/photo-1587486913049-53fc88980cfc?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80',
                    isBestSeller: true,
                    views: 1900,
                    rating: 4.7
                }
            ];
            
            // Current page state
            let currentPage = 'home';
            let currentCategory = '';
            let currentFilter = '';
            
            // Cart functionality
            let cart = [];
            const cartIcon = document.getElementById('cart-icon');
            const cartModal = document.getElementById('cart-modal');
            const closeCart = document.getElementById('close-cart');
            const cartItemsContainer = document.getElementById('cart-items');
            const cartCount = document.getElementById('cart-count');
            const cartTotal = document.getElementById('cart-total');
            const subtotal = document.getElementById('subtotal');
            const shipping = document.getElementById('shipping');
            const discount = document.getElementById('discount');
            const toast = document.getElementById('toast');
            const toastMessage = document.getElementById('toast-message');
            
            // Quick view functionality
            const quickViewModal = document.getElementById('quick-view-modal');
            const closeQuickView = document.getElementById('close-quick-view');
            const quickViewImg = document.getElementById('quick-view-img');
            const quickViewTitle = document.getElementById('quick-view-title');
            const quickViewPrice = document.getElementById('quick-view-price');
            const quickViewAddToCart = document.getElementById('quick-view-add-to-cart');
            let currentProductInQuickView = null;
            
            // Auth functionality
            const authModal = document.getElementById('auth-modal');
            const closeAuth = document.getElementById('close-auth');
            const loginTab = document.getElementById('login-tab');
            const signupTab = document.getElementById('signup-tab');
            const loginForm = document.getElementById('login-form');
            const signupForm = document.getElementById('signup-form');
            const loginLink = document.getElementById('login-link');
            
            // Price range slider
            const rangeMin = document.querySelector('.range-min');
            const rangeMax = document.querySelector('.range-max');
            const progress = document.querySelector('.progress');
            const minPrice = document.getElementById('min-price');
            const maxPrice = document.getElementById('max-price');
            
            // Page elements
            const homePage = document.getElementById('home-page');
            const productsPage = document.getElementById('products-page');
            const discountsPage = document.getElementById('discounts-page');
            const bestSellersPage = document.getElementById('best-sellers-page');
            const newArrivalsPage = document.getElementById('new-arrivals-page');
            const featuredPage = document.getElementById('featured-page');
            const aboutPage = document.getElementById('about-page');
            const contactPage = document.getElementById('contact-page');
            const supportPage = document.getElementById('support-page');
            const categoryPage = document.getElementById('category-page');
            
            // Links
            const homeLink = document.getElementById('home-link');
            const discountsLink = document.getElementById('discounts-link');
            const bestSellersLink = document.getElementById('best-sellers-link');
            const newArrivalsLink = document.getElementById('new-arrivals-link');
            const featuredLink = document.getElementById('featured-link');
            const aboutLink = document.getElementById('about-link');
            const contactLink = document.getElementById('contact-link');
            const supportLink = document.getElementById('support-link');
            const viewProductsBtn = document.getElementById('view-products-btn');
            
            // Category links
            const categoryLinks = document.querySelectorAll('.category-link');
            
            // Filter links
            const cheapestFilter = document.getElementById('cheapest-filter');
            const expensiveFilter = document.getElementById('expensive-filter');
            const popularFilter = document.getElementById('popular-filter');
            const topRatedFilter = document.getElementById('top-rated-filter');
            
            // Search
            const searchInput = document.getElementById('search-input');
            const searchBtn = document.getElementById('search-btn');
            
            // Format price with commas
            function formatPrice(price) {
                return new Intl.NumberFormat('fa-IR').format(price) + ' تومان';
            }
            
            // Show page
            function showPage(page) {
                // Hide all pages
                homePage.style.display = 'none';
                productsPage.style.display = 'none';
                discountsPage.style.display = 'none';
                bestSellersPage.style.display = 'none';
                newArrivalsPage.style.display = 'none';
                featuredPage.style.display = 'none';
                aboutPage.style.display = 'none';
                contactPage.style.display = 'none';
                supportPage.style.display = 'none';
                categoryPage.style.display = 'none';
                
                // Show selected page
                switch(page) {
                    case 'home':
                        homePage.style.display = 'block';
                        break;
                    case 'products':
                        productsPage.style.display = 'block';
                        displayAllProducts();
                        break;
                    case 'discounts':
                        discountsPage.style.display = 'block';
                        displayDiscountProducts();
                        break;
                    case 'best-sellers':
                        bestSellersPage.style.display = 'block';
                        displayBestSellers();
                        break;
                    case 'new-arrivals':
                        newArrivalsPage.style.display = 'block';
                        displayNewArrivals();
                        break;
                    case 'featured':
                        featuredPage.style.display = 'block';
                        displayFeaturedProducts();
                        break;
                    case 'about':
                        aboutPage.style.display = 'block';
                        break;
                    case 'contact':
                        contactPage.style.display = 'block';
                        break;
                    case 'support':
                        supportPage.style.display = 'block';
                        break;
                    case 'category':
                        categoryPage.style.display = 'block';
                        break;
                }
                
                currentPage = page;
            }
            
            // Display products
            function displayProducts() {
                const productsContainer = document.getElementById('products-container');
                const bestSellersContainer = document.getElementById('best-sellers-container');
                const newArrivalsContainer = document.getElementById('new-arrivals-container');
                
                productsContainer.innerHTML = '';
                bestSellersContainer.innerHTML = '';
                newArrivalsContainer.innerHTML = '';
                
                // Filter featured products (3 items)
                const featuredProducts = products.filter(p => p.isFeatured).slice(0, 3);
                
                // Filter best sellers (6 items)
                const bestSellers = products.filter(p => p.isBestSeller).slice(0, 6);
                
                // Filter new arrivals (6 items)
                const newArrivals = products.filter(p => p.isNew).slice(0, 6);
                
                featuredProducts.forEach(product => {
                    productsContainer.appendChild(createProductElement(product));
                });
                
                bestSellers.forEach(product => {
                    bestSellersContainer.appendChild(createProductElement(product));
                });
                
                newArrivals.forEach(product => {
                    newArrivalsContainer.appendChild(createProductElement(product));
                });
            }
            
            // Display all products
            function displayAllProducts() {
                const container = document.getElementById('all-products-container');
                container.innerHTML = '';
                
                let filteredProducts = [...products];
                
                // Apply category filter
                if (currentCategory) {
                    filteredProducts = filteredProducts.filter(p => p.category === currentCategory);
                }
                
                // Apply price filter
                const minPriceValue = parseInt(rangeMin.value);
                const maxPriceValue = parseInt(rangeMax.value);
                filteredProducts = filteredProducts.filter(p => p.price >= minPriceValue && p.price <= maxPriceValue);
                
                // Apply other filters
                if (currentFilter === 'cheapest') {
                    filteredProducts.sort((a, b) => a.price - b.price);
                } else if (currentFilter === 'expensive') {
                    filteredProducts.sort((a, b) => b.price - a.price);
                } else if (currentFilter === 'popular') {
                    filteredProducts.sort((a, b) => b.views - a.views);
                } else if (currentFilter === 'top-rated') {
                    filteredProducts.sort((a, b) => b.rating - a.rating);
                }
                
                filteredProducts.forEach(product => {
                    container.appendChild(createProductElement(product));
                });
            }
            
            // Display discount products
            function displayDiscountProducts() {
                const container = document.getElementById('discounts-container');
                container.innerHTML = '';
                
                const discountedProducts = products.filter(p => p.originalPrice);
                
                discountedProducts.forEach(product => {
                    container.appendChild(createProductElement(product));
                });
            }
            
            // Display best sellers
            function displayBestSellers() {
                const container = document.getElementById('best-sellers-page-container');
                container.innerHTML = '';
                
                const bestSellers = products.filter(p => p.isBestSeller);
                
                bestSellers.forEach(product => {
                    container.appendChild(createProductElement(product));
                });
            }
            
            // Display new arrivals
            function displayNewArrivals() {
                const container = document.getElementById('new-arrivals-page-container');
                container.innerHTML = '';
                
                const newArrivals = products.filter(p => p.isNew);
                
                newArrivals.forEach(product => {
                    container.appendChild(createProductElement(product));
                });
            }
            
            // Display featured products
            function displayFeaturedProducts() {
                const container = document.getElementById('featured-container');
                container.innerHTML = '';
                
                const featuredProducts = products.filter(p => p.isFeatured);
                
                featuredProducts.forEach(product => {
                    container.appendChild(createProductElement(product));
                });
            }
            
            // Display category products
            function displayCategoryProducts(category) {
                const container = document.getElementById('category-products-container');
                const title = document.getElementById('category-title');
                const description = document.getElementById('category-description');
                
                container.innerHTML = '';
                currentCategory = category;
                
                title.textContent = category;
                description.textContent = `محصولات دسته‌بندی ${category}`;
                
                const categoryProducts = products.filter(p => p.category === category);
                
                categoryProducts.forEach(product => {
                    container.appendChild(createProductElement(product));
                });
                
                showPage('category');
            }
            
            // Create product element
            function createProductElement(product) {
                const productElement = document.createElement('div');
                productElement.className = 'product-card';
                productElement.setAttribute('data-id', product.id);
                
                const discountPercent = product.originalPrice ? 
                    Math.round(((product.originalPrice - product.price) / product.originalPrice) * 100) : 0;
                
                productElement.innerHTML = `
                    ${product.isNew ? `<div class="product-badge">جدید</div>` : ''}
                    <div class="product-image">
                        <img src="${product.image}" alt="${product.title}">
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">${product.title}</h3>
                        <span class="product-category">${product.category}</span>
                        <div class="product-rating">
                            <div class="stars">
                                ${generateStars(product.rating)}
                            </div>
                            <span class="count">(${Math.floor(Math.random() * 100) + 1} نظر)</span>
                        </div>
                        <div class="product-price">
                            <span class="current-price">${formatPrice(product.price)}</span>
                            ${product.originalPrice ? `
                                <span class="original-price">${formatPrice(product.originalPrice)}</span>
                                <span class="discount">${discountPercent}%</span>
                            ` : ''}
                        </div>
                        <div class="product-actions">
                            <button class="add-to-cart"><i class="fas fa-cart-plus"></i> افزودن</button>
                            <div class="action-buttons">
                                <button class="quick-view"><i class="fas fa-eye"></i></button>
                                <button class="compare"><i class="fas fa-exchange-alt"></i></button>
                                <button class="wishlist"><i class="far fa-heart"></i></button>
                            </div>
                        </div>
                    </div>
                `;
                
                // Add event listeners
                const addToCartBtn = productElement.querySelector('.add-to-cart');
                const wishlistBtn = productElement.querySelector('.wishlist');
                const quickViewBtn = productElement.querySelector('.quick-view');
                
                addToCartBtn.addEventListener('click', () => addToCart(product));
                wishlistBtn.addEventListener('click', () => toggleWishlist(wishlistBtn));
                quickViewBtn.addEventListener('click', () => showQuickView(product));
                
                return productElement;
            }
            
            // Generate star rating
            function generateStars(rating) {
                let stars = '';
                const fullStars = Math.floor(rating);
                const hasHalfStar = rating % 1 >= 0.5;
                
                for (let i = 0; i < fullStars; i++) {
                    stars += '<i class="fas fa-star"></i>';
                }
                
                if (hasHalfStar) {
                    stars += '<i class="fas fa-star-half-alt"></i>';
                }
                
                const emptyStars = 5 - fullStars - (hasHalfStar ? 1 : 0);
                for (let i = 0; i < emptyStars; i++) {
                    stars += '<i class="far fa-star"></i>';
                }
                
                return stars;
            }
            
            // Add to cart function
            function addToCart(product) {
                const existingItem = cart.find(item => item.id === product.id);
                
                if (existingItem) {
                    existingItem.quantity += 1;
                } else {
                    cart.push({
                        ...product,
                        quantity: 1
                    });
                }
                
                updateCart();
                showToast('محصول به سبد خرید اضافه شد');
            }
            
            // Toggle wishlist
            function toggleWishlist(button) {
                button.classList.toggle('active');
                if (button.classList.contains('active')) {
                    showToast('محصول به علاقه‌مندی‌ها اضافه شد');
                } else {
                    showToast('محصول از علاقه‌مندی‌ها حذف شد');
                }
            }
            
            // Show quick view
            function showQuickView(product) {
                currentProductInQuickView = product;
                quickViewImg.src = product.image;
                quickViewTitle.textContent = product.title;
                quickViewPrice.textContent = formatPrice(product.price);
                quickViewModal.classList.add('active');
                
                document.body.style.overflow = 'hidden';
            }
            
            // Close quick view
            function closeQuickViewModal() {
                quickViewModal.classList.remove('active');
                document.body.style.overflow = 'auto';
            }
            
            // Update cart
            function updateCart() {
                cartCount.textContent = cart.reduce((total, item) => total + item.quantity, 0);
                
                // Update cart items
                cartItemsContainer.innerHTML = '';
                
                if (cart.length === 0) {
                    cartItemsContainer.innerHTML = `
                        <div class="empty-cart">
                            <i class="fas fa-shopping-cart"></i>
                            <p>سبد خرید شما خالی است</p>
                            <button class="continue-shopping">ادامه خرید</button>
                        </div>
                    `;
                    
                    const continueShoppingBtn = cartItemsContainer.querySelector('.continue-shopping');
                    continueShoppingBtn.addEventListener('click', () => {
                        cartModal.classList.remove('active');
                    });
                } else {
                    cart.forEach(item => {
                        const cartItemElement = document.createElement('div');
                        cartItemElement.className = 'cart-item';
                        cartItemElement.setAttribute('data-id', item.id);
                        
                        cartItemElement.innerHTML = `
                            <button class="cart-item-remove"><i class="fas fa-times"></i></button>
                            <div class="cart-item-image">
                                <img src="${item.image}" alt="${item.title}">
                            </div>
                            <div class="cart-item-details">
                                <h3 class="cart-item-title">${item.title}</h3>
                                <span class="cart-item-price">${formatPrice(item.price)}</span>
                                <div class="cart-item-actions">
                                    <button class="remove-item">حذف</button>
                                    <div class="quantity-control">
                                        <button class="quantity-btn decrease">-</button>
                                        <span class="quantity">${item.quantity}</span>
                                        <button class="quantity-btn increase">+</button>
                                    </div>
                                </div>
                            </div>
                        `;
                        
                        const removeBtn = cartItemElement.querySelector('.remove-item');
                        const decreaseBtn = cartItemElement.querySelector('.decrease');
                        const increaseBtn = cartItemElement.querySelector('.increase');
                        const quantityElement = cartItemElement.querySelector('.quantity');
                        const cartItemRemove = cartItemElement.querySelector('.cart-item-remove');
                        
                        removeBtn.addEventListener('click', () => removeFromCart(item.id));
                        cartItemRemove.addEventListener('click', () => removeFromCart(item.id));
                        decreaseBtn.addEventListener('click', () => updateQuantity(item.id, -1));
                        increaseBtn.addEventListener('click', () => updateQuantity(item.id, 1));
                        
                        cartItemsContainer.appendChild(cartItemElement);
                    });
                }
                
                // Update cart totals
                const subtotalValue = cart.reduce((total, item) => total + (item.price * item.quantity), 0);
                const shippingValue = subtotalValue > 500000 ? 0 : 25000;
                const discountValue = 0; // Can be calculated based on promotions
                const totalValue = subtotalValue + shippingValue - discountValue;
                
                subtotal.textContent = formatPrice(subtotalValue);
                shipping.textContent = formatPrice(shippingValue);
                discount.textContent = formatPrice(discountValue);
                cartTotal.textContent = formatPrice(totalValue);
            }
            
            // Remove from cart
            function removeFromCart(productId) {
                cart = cart.filter(item => item.id !== productId);
                updateCart();
                showToast('محصول از سبد خرید حذف شد');
            }
            
            // Update quantity
            function updateQuantity(productId, change) {
                const item = cart.find(item => item.id === productId);
                
                if (item) {
                    item.quantity += change;
                    
                    if (item.quantity <= 0) {
                        removeFromCart(productId);
                    } else {
                        updateCart();
                    }
                }
            }
            
            // Show toast notification
            function showToast(message) {
                toastMessage.textContent = message;
                toast.classList.add('show');
                
                setTimeout(() => {
                    toast.classList.remove('show');
                }, 3000);
            }
            
            // Initialize price range slider
            function initPriceRangeSlider() {
                let minVal = parseInt(rangeMin.value);
                let maxVal = parseInt(rangeMax.value);
                
                rangeMin.addEventListener('input', function() {
                    minVal = parseInt(this.value);
                    if (minVal > maxVal) {
                        this.value = maxVal;
                        minVal = maxVal;
                    }
                    updatePriceRange();
                });
                
                rangeMax.addEventListener('input', function() {
                    maxVal = parseInt(this.value);
                    if (maxVal < minVal) {
                        this.value = minVal;
                        maxVal = minVal;
                    }
                    updatePriceRange();
                });
                
                function updatePriceRange() {
                    minPrice.textContent = formatPrice(minVal);
                    maxPrice.textContent = formatPrice(maxVal);
                    progress.style.left = (minVal / rangeMin.max) * 100 + '%';
                    progress.style.right = 100 - (maxVal / rangeMax.max) * 100 + '%';
                    
                    // Update products if on products page
                    if (currentPage === 'products') {
                        displayAllProducts();
                    }
                }
                
                updatePriceRange();
            }
            
            // Search products
            function searchProducts(query) {
                if (query.trim() === '') return;
                
                showPage('products');
                currentCategory = '';
                currentFilter = '';
                
                const container = document.getElementById('all-products-container');
                container.innerHTML = '';
                
                const filteredProducts = products.filter(p => 
                    p.title.includes(query) || 
                    p.category.includes(query)
                );
                
                if (filteredProducts.length === 0) {
                    container.innerHTML = `
                        <div style="grid-column: 1 / -1; text-align: center; padding: 2rem; color: #888;">
                            <i class="fas fa-search" style="font-size: 2rem; margin-bottom: 1rem;"></i>
                            <p>هیچ محصولی یافت نشد</p>
                        </div>
                    `;
                } else {
                    filteredProducts.forEach(product => {
                        container.appendChild(createProductElement(product));
                    });
                }
            }
            
            // Event listeners
            cartIcon.addEventListener('click', () => {
                cartModal.classList.add('active');
                document.body.style.overflow = 'hidden';
            });
            
            closeCart.addEventListener('click', () => {
                cartModal.classList.remove('active');
                document.body.style.overflow = 'auto';
            });
            
            closeQuickView.addEventListener('click', closeQuickViewModal);
            
            quickViewAddToCart.addEventListener('click', () => {
                if (currentProductInQuickView) {
                    addToCart(currentProductInQuickView);
                    closeQuickViewModal();
                }
            });
            
            // Auth modal
            loginLink.addEventListener('click', () => {
                authModal.classList.add('active');
                document.body.style.overflow = 'hidden';
            });
            
            closeAuth.addEventListener('click', () => {
                authModal.classList.remove('active');
                document.body.style.overflow = 'auto';
            });
            
            loginTab.addEventListener('click', () => {
                loginTab.classList.add('active');
                signupTab.classList.remove('active');
                loginForm.style.display = 'block';
                signupForm.style.display = 'none';
            });
            
            signupTab.addEventListener('click', () => {
                signupTab.classList.add('active');
                loginTab.classList.remove('active');
                signupForm.style.display = 'block';
                loginForm.style.display = 'none';
            });
            
            // Page navigation
            homeLink.addEventListener('click', () => showPage('home'));
            discountsLink.addEventListener('click', () => showPage('discounts'));
            bestSellersLink.addEventListener('click', () => showPage('best-sellers'));
            newArrivalsLink.addEventListener('click', () => showPage('new-arrivals'));
            featuredLink.addEventListener('click', () => showPage('featured'));
            aboutLink.addEventListener('click', () => showPage('about'));
            contactLink.addEventListener('click', () => showPage('contact'));
            supportLink.addEventListener('click', () => showPage('support'));
            viewProductsBtn.addEventListener('click', () => showPage('products'));
            
            // Category links
            categoryLinks.forEach(link => {
                link.addEventListener('click', () => {
                    const category = link.getAttribute('data-category');
                    displayCategoryProducts(category);
                });
            });
            
            // Filter links
            cheapestFilter.addEventListener('click', () => {
                currentFilter = 'cheapest';
                showPage('products');
                displayAllProducts();
            });
            
            expensiveFilter.addEventListener('click', () => {
                currentFilter = 'expensive';
                showPage('products');
                displayAllProducts();
            });
            
            popularFilter.addEventListener('click', () => {
                currentFilter = 'popular';
                showPage('products');
                displayAllProducts();
            });
            
            topRatedFilter.addEventListener('click', () => {
                currentFilter = 'top-rated';
                showPage('products');
                displayAllProducts();
            });
            
            // Search
            searchBtn.addEventListener('click', () => {
                searchProducts(searchInput.value);
            });
            
            searchInput.addEventListener('keypress', (e) => {
                if (e.key === 'Enter') {
                    searchProducts(searchInput.value);
                }
            });
            
            // Close modals when clicking outside
            window.addEventListener('click', (e) => {
                if (e.target === cartModal) {
                    cartModal.classList.remove('active');
                    document.body.style.overflow = 'auto';
                }
                
                if (e.target === quickViewModal) {
                    closeQuickViewModal();
                }
                
                if (e.target === authModal) {
                    authModal.classList.remove('active');
                    document.body.style.overflow = 'auto';
                }
            });
            
            // Initialize
            displayProducts();
            initPriceRangeSlider();
            showPage('home');
            
            // Animate elements on scroll
            const animateOnScroll = () => {
                const elements = document.querySelectorAll('.product-card, .category-title, .banner');
                
                elements.forEach(element => {
                    const elementPosition = element.getBoundingClientRect().top;
                    const screenPosition = window.innerHeight / 1.2;
                    
                    if (elementPosition < screenPosition) {
                        element.style.animation = 'fadeInUp 0.5s ease forwards';
                    }
                });
            };
            
            window.addEventListener('scroll', animateOnScroll);
            animateOnScroll(); // Run once on page load
        });
    </script>
</body>
</html>
# -
سایت سوپر مارکت به کمک html,css,javascript
