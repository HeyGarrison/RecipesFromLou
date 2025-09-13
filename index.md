---
layout: default
title: "Recipes From Lou"
---

# Welcome to Lou's Recipe Collection

{{ site.description }}

## About This Collection

This website contains Lou's cherished recipe collection, gathered over 50 years of marriage from family, friends, co-workers, magazines, and treasured memories. Each recipe tells a story and carries forward the love of cooking that Lou learned from her grandmother, Mama Franklin.

## Search Recipes

<div class="search-container">
  <input type="text" id="search-input" placeholder="Search recipes by name, ingredients, or type..." />
  <ul id="results-container"></ul>
</div>

## Browse Recipes by Category

<div class="recipe-categories">
  <div class="category-grid">
    <div class="category-card">
      <h3><a href="/RecipesFromLou/categories/appetizers-beverages">🥗 Appetizers & Beverages</a></h3>
      <p>Start your meal right and quench your thirst with appetizers and drinks.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/converted/breads/">🥖 Breads</a></h3>
      <p>From breakfast breads to cornbread, comfort food at its finest.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/converted/cakes/">🍰 Cakes</a></h3>
      <p>Sweet endings with chocolate, red velvet, cheesecakes and more.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/categories/baking-cookies">🍪 Baking & Cookies</a></h3>
      <p>Classic cookies, bars, and sweet baked treats for every occasion.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/categories/desserts-sweets">🍮 Desserts & Sweets</a></h3>
      <p>Indulgent desserts, pies, candy, and sweet confections.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/categories/main-courses">🥩 Main Courses</a></h3>
      <p>Hearty main dishes with meats, seafood, and satisfying casseroles.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/converted/poultry/">🍗 Poultry</a></h3>
      <p>Chicken dishes and stuffings for family gatherings.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/categories/sides-salads">🥗 Sides & Salads</a></h3>
      <p>Fresh vegetables, salads, and flavorful sauces to complement meals.</p>
    </div>
    
    <div class="category-card">
      <h3><a href="/RecipesFromLou/categories/preservation-canning">🥫 Preservation & Canning</a></h3>
      <p>Traditional preservation methods and hearty comfort soups.</p>
    </div>
  </div>
</div>

## More Categories

- [🍫 Candy](/RecipesFromLou/converted/candy) - Sweet confections and treats
- [🥫 Canning & Preserves](/RecipesFromLou/converted/canning-and-preserves) - Preserve the harvest
- [🍽️ Casseroles](/RecipesFromLou/converted/casseroles) - One-dish family meals  
- [🧁 Icings & Frostings](/RecipesFromLou/converted/icings-and-frostings) - Perfect cake toppers
- [🥧 Pies](/RecipesFromLou/converted/pies) - Classic and creative pies
- [🍯 Sauces](/RecipesFromLou/converted/sauces) - Flavor enhancers
- [🍪 Bars & Squares](/RecipesFromLou/converted/bars-and-squares) - Easy sweet treats

## Special Pages

- [📖 Introduction](/RecipesFromLou/converted/introduction) - Lou's dedication and family history
- [📋 Recipe Index](/RecipesFromLou/converted/index-for-recipes) - Complete recipe listing
- [👨‍👩‍👧‍👦 Index for Chipmans](/RecipesFromLou/converted/index-for-chipmans) - Family favorites

---

*This collection preserves not just recipes, but memories, traditions, and the love that goes into every home-cooked meal.*

<script src="{{ '/assets/js/simple-jekyll-search.min.js' | prepend: site.baseurl }}"></script>

<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '{{ "/search.json" | prepend: site.baseurl }}',
  searchResultTemplate: '<li><a href="{url}" title="{category}">{title}</a> <small>({category})</small></li>',
  noResultsText: 'No recipes found matching your search.',
  limit: 10,
  fuzzy: false,
  exclude: ['url']
});
</script>

<style>
.search-container {
  margin: 2rem 0;
  padding: 1.5rem;
  background: #f8f9fa;
  border-radius: 8px;
  border: 1px solid #e9ecef;
}

#search-input {
  width: 100%;
  padding: 12px;
  font-size: 16px;
  border: 2px solid #ddd;
  border-radius: 6px;
  box-sizing: border-box;
  margin-bottom: 1rem;
}

#search-input:focus {
  outline: none;
  border-color: #007bff;
  box-shadow: 0 0 5px rgba(0,123,255,0.3);
}

#results-container {
  list-style: none;
  padding: 0;
  margin: 0;
  max-height: 400px;
  overflow-y: auto;
}

#results-container li {
  padding: 8px 0;
  border-bottom: 1px solid #eee;
}

#results-container li:last-child {
  border-bottom: none;
}

#results-container a {
  color: #007bff;
  text-decoration: none;
  font-weight: 500;
}

#results-container a:hover {
  text-decoration: underline;
}

#results-container small {
  color: #666;
  font-style: italic;
}

@media (max-width: 600px) {
  .search-container {
    margin: 1rem -1rem;
    padding: 1rem;
    border-radius: 0;
    border-left: none;
    border-right: none;
  }
}
</style>