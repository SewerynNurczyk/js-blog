 const activeArticles = document.querySelectorAll('.post .active');

    for (let activeArticle of activeArticles) {
        activeArticle.classList.remove('active');
    }