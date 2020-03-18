1.	Dmitriy Semenenko
2.	Tel +7-926-058-95-30
3.	• Im specialist with a passion for design. • Im able to captivate customers with engaging visuals.!!! • I harness the potential of visual art to create content that communicates clearly and in the most effective way. • I`m expert at visual design, Adobe Photoshop, Adobe Illustrator, Adobe flash, Coral draw, html, CSS, JS. • English language – advanced level. • I have a great practical experience at visual design. • Subtly feel new trends in design.Smile • Quick –leaner. • Strong communication skills and the ability to incorporate feedback quickly
4.	-organize the local marketing programs and events, building and maintaining relations with key opinion-leaders at the country level; -developing concept of websites; -developing website`s content; -checkout HTML & CSS code; -maintaining websites;
5.	https://shoshin.me/company/staff/filatova-vera/
6.	Code examples (LATEST) (function() { const cnv = document.getElementById("cnv"); const ctx = cnv.getContext("2d");
let mouse = new Vec2(); let distanceVec = new Vec2(); let myImg = new ImgSceneObject( new Image(),
'http://www.java-forums.org/attachments/java-2d/1449d1319003532t-tank-game-help-please-tankeast.jpg', 50, 50, new Vec2(200, 200) ); let angle = 0; let translationVec = new Vec2(myImg.pos.x, myImg.pos.y); let direction = new Vec2(); let translationSpeed = 2;
function initApp() { cnv.width = window.innerWidth; cnv.height = window.innerHeight; document.onmousemove = mousemove; }
function Vec2(x=0, y=0) { this.x = x; this.y = y;
this.add = function(v) {
  this.x += v.x;
  this.y += v.y;
  return this;
}; 

this.sub = function(v) {
  this.x -= v.x;
  this.y -= v.y;
  return this;
}; 

this.multScalar = function(s) {
  this.x *= s; this.y *= s;
  return this;
}; 

this.dot = function(v) {
  return this.x*v.x + this.y*v.y;
}; 

this.rotate = function(angle) {
  this.x = this.x*Math.cos(angle) - y*Math.sin(angle);
  this.y = this.x*Math.sin(angle) + y*Math.cos(angle);
  return this;
}; 1

this.translate = function(v) {
  this.add(v);
  return this;
};

this.length = function() {
  return Math.sqrt(this.x*this.x + this.y*this.y);
};

this.normalize = function() {
  const invLength = 1.0/this.length();
  this.x *= invLength;
  this.y *= invLength;
  return this;
};
}a
function ImgSceneObject(img, src, w, h, imageCenter) { loaded = false; img.onload = function() { loaded = true; } img.src = src; this.pos = imageCenter; this.w = w; this.h = h;
this.update = function(angle, v) { ctx.save();
ctx.translate(this.pos.x, this.pos.y); ctx.rotate(angle);
this.pos.x = v.x; this.pos.y = v.y;
if (loaded) {
ctx.drawImage(img, -this.w/2, -this.h/2, this.w, this.h); } ctx.restore(); }; }
function updateScene() { renderTarget(); myImg.update(angle, translationVec); distanceVec.x = mouse.x - myImg.pos.x; distanceVec.y = mouse.y - myImg.pos.y; if (distanceVec.length() > 10) { translationVec.add(direction);
} }
function renderTarget() { ctx.beginPath(); ctx.arc(mouse.x - 7, mouse.y - 7, 7, 0, Math.PI * 2); ctx.fill(); ctx.closePath(); }
function gameloop() { ctx.clearRect(0, 0, cnv.width, cnv.height); updateScene(); id = requestAnimationFrame(gameloop); }
function mousemove(e) {
mouse.x = e.clientX; mouse.y = e.clientY;
direction.x = mouse.x; direction.y = mouse.y;
angle = Math.atan2(mouse.y-myImg.pos.y, mouse.x-myImg.pos.x); direction.sub(myImg.pos).normalize().multScalar(translationSpeed); };
initApp(); gameloop(); }());
6.	Experience https://codepen.io/alexzaworski/pen/mEkvAG https://codepen.io/hexagoncircle/pen/akWOdE https://codepen.io/bob6664569/pen/rOzmve
7.	Education Professional development, courses 2009 web-designer private school, web-designer 2009 SEO specialist private school, SEO specialist Tests, examinations 2008 driving test driving school"Doseaf", exellent
8.	English (elaborate on what kind of practice you had, if any, how long it lasted and so on) n
