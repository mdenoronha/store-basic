if(!window.scripts) {
  window.scripts = {};
};

scripts.init = function(section, script) {
  let sections = document.querySelectorAll('.shopify-section' + section);
  sections.forEach(function(section) {
    script.init(section);
  });
};

// Header Section
scripts.Header = {
  init: function(section) {
    this.mobileMenu(section)
  },

  mobileMenu: function(section) {
    let selectors = {
      mobileMenuButton: section.querySelector('#mobile_menu'),
      body: document.querySelector('body')
    };

    // Open/close mobile menu
    selectors.mobileMenuButton.addEventListener('click', function() {
      selectors.body.classList.toggle('header__mobile-menu--open')
    });

    window.FontAwesomeConfig = {
      searchPseudoElements: true
    };
  }
};

// Featured Products Section
scripts.FeaturedProducts = {
  init: function(section) {
    this.productForm(section)
  },

  // Remove disabled from form if variant is selected
  productForm: function(section) {
    let selectors = {
      productSelect: section.querySelectorAll('.featured-products__select')
    };

    selectors.productSelect.forEach(function(select) {
      select.addEventListener('change', function(e) {
        let changedSelect = e.target;

        if(changedSelect.options[changedSelect.selectedIndex].hasAttribute('disabled')) {
          changedSelect.nextElementSibling.setAttribute('disabled')
        } else {
          changedSelect.nextElementSibling.removeAttribute('disabled')
        }
      })
    });
  }
};

document.addEventListener("DOMContentLoaded", function() {
    // Initialise a section's JS by passing the section's class and relevant object
    scripts.init('.header-block', scripts.Header);
    scripts.init('.featured-product-collection', scripts.FeaturedProducts);
});