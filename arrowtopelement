document.addEventListener('DOMContentLoaded', function() {
            var widget = document.getElementById('widget');
            var lastScrollTop = 0;
          window.addEventListener('scroll', function() {
                var currentScrollTop = window.pageYOffset || document.documentElement.scrollTop;

                if (currentScrollTop > lastScrollTop && currentScrollTop > 100) {
                    // Scroll Down
                    widget.classList.add('hidden');
                } else {
                    // Scroll Up
                    widget.classList.remove('hidden');
                }

                lastScrollTop = currentScrollTop <= 0 ? 0 : currentScrollTop; // For Mobile or negative scrolling
            });
        });
