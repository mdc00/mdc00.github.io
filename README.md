# Fam-Photos-
var photos = [
    (https://photos.google.com/u/6/share/AF1QipMF6oeymnt9nd0708IDQ778apxLDKZlVu_w0cXAhtMula2lM8wM2Gl0beoBEa7h_w/photo/AF1QipPP376zaPgNob0ipoQ_wX8VxHP5GbCBChCPaatr?key=c01sajQ1dmo0RVZGenRIcDN4UjBUcERkampqZ0lB),
    (https://photos.google.com/u/6/share/AF1QipMF6oeymnt9nd0708IDQ778apxLDKZlVu_w0cXAhtMula2lM8wM2Gl0beoBEa7h_w/photo/AF1QipPYlUaAc_jMZf_HVtISW8kEAMMeNqiGP5r6fFQH?key=c01sajQ1dmo0RVZGenRIcDN4UjBUcERkampqZ0lB),
    (https://photos.google.com/u/6/share/AF1QipMF6oeymnt9nd0708IDQ778apxLDKZlVu_w0cXAhtMula2lM8wM2Gl0beoBEa7h_w/photo/AF1QipPWnt-5dEjbaQWpiaumXWmiggxUbIm0XmO3B_6S?key=c01sajQ1dmo0RVZGenRIcDN4UjBUcERkampqZ0lB),
    // ... add all photo URLs here
];

function getRandomPhoto() {
    var randomIndex = Math.floor(Math.random() * photos.length);
    window.location.href = photos[randomIndex]; // Redirects to the random photo
}

window.onload = getRandomPhoto; // Calls the function when the page loads
