document.getElementById('newsForm').addEventListener('submit', function(event) {
    event.preventDefault();
    
    const title = document.getElementById('title').value;
    const content = document.getElementById('content').value;
    
    const article = document.createElement('article');
    const h3 = document.createElement('h3');
    h3.textContent = title;
    const p = document.createElement('p');
    p.textContent = content;
    
    article.appendChild(h3);
    article.appendChild(p);
    
    document.querySelector('.news').appendChild(article);
    
    document.getElementById('newsForm').reset();
});
