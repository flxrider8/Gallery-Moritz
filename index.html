<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Atelier — Kunstgalerie</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400;1,500&family=Cinzel:wght@400;500;600&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
:root {
  --black: #070706;
  --dark: #0e0d0b;
  --surface: #141310;
  --surface2: #1c1a16;
  --gold: #c8a951;
  --gold-l: #e8d5a3;
  --gold-d: #8b6914;
  --text: #f0ebe0;
  --muted: #8a8276;
  --border: rgba(200,169,81,0.18);
}
html { scroll-behavior: smooth; }
body { background: var(--black); color: var(--text); font-family: 'Cormorant Garamond', Georgia, serif; overflow-x: hidden; cursor: crosshair; }
::-webkit-scrollbar { width: 3px; }
::-webkit-scrollbar-track { background: var(--black); }
::-webkit-scrollbar-thumb { background: var(--gold-d); }

body::after {
  content:''; position:fixed; inset:0; pointer-events:none; z-index:9999; opacity:0.35;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='300' height='300'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.05'/%3E%3C/svg%3E");
}

/* NAV */
nav {
  position:fixed; top:0; left:0; right:0; z-index:200;
  padding:1.6rem 4rem; display:flex; justify-content:space-between; align-items:center;
  background:linear-gradient(to bottom,rgba(7,7,6,0.9) 0%,transparent 100%);
  transition:background 0.4s;
}
nav.scrolled { background:rgba(7,7,6,0.97); border-bottom:1px solid var(--border); }
.nav-logo { font-family:'Cinzel',serif; font-size:1.05rem; letter-spacing:0.35em; color:var(--gold); cursor:pointer; user-select:none; }
.nav-links { display:flex; gap:2.5rem; list-style:none; }
.nav-links a { font-size:0.68rem; letter-spacing:0.28em; text-transform:uppercase; color:var(--muted); text-decoration:none; transition:color 0.3s; }
.nav-links a:hover { color:var(--gold); }

/* HERO */
.hero { height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; position:relative; overflow:hidden; }
.hero-bg { position:absolute; inset:0; background:radial-gradient(ellipse 80% 55% at 50% 40%,rgba(139,105,20,0.14),transparent 70%),radial-gradient(ellipse 50% 40% at 15% 75%,rgba(100,70,10,0.08),transparent 60%),var(--black); }
#particles-canvas { position:absolute; inset:0; pointer-events:none; }
.hero-eyebrow { font-size:0.65rem; letter-spacing:0.55em; text-transform:uppercase; color:var(--gold); margin-bottom:1.8rem; opacity:0; animation:fadeUp 1s ease 0.4s forwards; }
.hero-title { font-size:clamp(4rem,11vw,10rem); font-weight:300; line-height:0.88; letter-spacing:-0.02em; color:var(--text); opacity:0; animation:fadeUp 1s ease 0.7s forwards; }
.hero-title em { font-style:italic; color:var(--gold); }
.hero-subtitle { margin-top:2.2rem; font-size:1rem; letter-spacing:0.22em; color:var(--muted); font-weight:300; opacity:0; animation:fadeUp 1s ease 1s forwards; }
.hero-rule { width:1px; height:90px; background:linear-gradient(to bottom,transparent,var(--gold),transparent); margin:3rem auto 0; opacity:0; animation:fadeUp 1s ease 1.3s forwards; }
.hero-scroll { position:absolute; bottom:2.5rem; left:50%; transform:translateX(-50%); display:flex; flex-direction:column; align-items:center; gap:0.5rem; opacity:0; animation:fadeUp 1s ease 1.6s forwards; }
.hero-scroll span { font-size:0.58rem; letter-spacing:0.45em; text-transform:uppercase; color:var(--muted); }
.scroll-bar { width:1px; height:45px; background:var(--gold-d); animation:scrollAnim 2.2s ease infinite; }
@keyframes scrollAnim { 0%,100%{transform:scaleY(1);opacity:0.5;} 50%{transform:scaleY(0.4);opacity:1;} }
@keyframes fadeUp { from{opacity:0;transform:translateY(22px);} to{opacity:1;transform:translateY(0);} }

/* SECTION HEADER */
.sec-head { text-align:center; padding:7rem 2rem 4rem; }
.sec-eye { font-size:0.62rem; letter-spacing:0.55em; text-transform:uppercase; color:var(--gold); margin-bottom:0.9rem; }
.sec-title { font-size:clamp(2.5rem,5vw,4.2rem); font-weight:300; font-style:italic; color:var(--text); }
.sec-line { width:55px; height:1px; background:var(--gold); margin:1.8rem auto; opacity:0.6; }

/* GALLERY */
.gallery-wrap { padding:0 4rem 9rem; max-width:1700px; margin:0 auto; }
.gallery-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(360px,1fr)); gap:5rem 4rem; }

/* PAINTING CARD */
.pcard { position:relative; opacity:0; transform:translateY(45px); transition:opacity 0.9s ease, transform 0.9s ease; }
.pcard.visible { opacity:1; transform:translateY(0); }

.p-wrapper { position:relative; display:block; cursor:pointer; }
.p-img-box { position:relative; overflow:hidden; aspect-ratio:4/3; }
.p-img-box img { width:100%; height:100%; object-fit:cover; display:block; transition:transform 0.9s cubic-bezier(0.25,0.46,0.45,0.94); }
.p-wrapper:hover .p-img-box img { transform:scale(1.045); }
.p-spot { position:absolute; inset:0; pointer-events:none; opacity:0; transition:opacity 0.25s; z-index:1; background:radial-gradient(circle 200px at 50% 50%,rgba(255,255,200,0.14),transparent 70%); }
.p-wrapper:hover .p-spot { opacity:1; }
.p-overlay { position:absolute; inset:0; background:linear-gradient(to top,rgba(7,7,6,0.88) 0%,transparent 55%); display:flex; align-items:flex-end; padding:1.4rem; opacity:0; transition:opacity 0.4s; z-index:2; }
.p-wrapper:hover .p-overlay { opacity:1; }
.p-overlay-title { font-style:italic; font-size:1.1rem; color:var(--text); }

/* FRAME STYLES */
.frame-ornate-gold .p-img-box {
  border:14px solid var(--gold);
  outline:2px solid rgba(200,169,81,0.25); outline-offset:4px;
  box-shadow:inset 0 0 0 2px var(--gold-d),inset 0 0 0 3px var(--gold),inset 0 0 0 5px var(--gold-d),0 35px 90px rgba(0,0,0,0.92),0 0 50px rgba(200,169,81,0.07);
}
.frame-modern-black .p-img-box {
  border:9px solid #111;
  box-shadow:inset 0 0 0 1px #2a2a2a,0 35px 90px rgba(0,0,0,0.92),0 0 0 1px #1f1f1f;
}
.frame-rustic-wood .p-img-box {
  border:16px solid #5a3419;
  box-shadow:inset 0 0 0 2px #7a4e2d,inset 0 0 0 4px #3c2310,0 35px 90px rgba(0,0,0,0.92);
}
.frame-silver .p-img-box {
  border:10px solid #888;
  box-shadow:inset 0 0 0 1px #ccc,inset 0 0 0 3px #666,inset 0 0 0 5px #bbb,0 35px 90px rgba(0,0,0,0.92);
}
.frame-white .p-img-box {
  border:12px solid #e8e4dc;
  box-shadow:inset 0 0 0 1px #ccc,0 35px 90px rgba(0,0,0,0.92);
}
.frame-none .p-img-box { box-shadow:0 35px 90px rgba(0,0,0,0.92); }

/* PAINTING INFO */
.p-info { padding:1.4rem 0.3rem 0; }
.p-meta { display:flex; justify-content:space-between; align-items:baseline; margin-bottom:0.45rem; }
.p-title { font-size:1.3rem; font-weight:400; font-style:italic; color:var(--text); letter-spacing:0.02em; }
.p-year { font-size:0.68rem; letter-spacing:0.22em; color:var(--gold); }
.p-desc { font-size:0.92rem; font-weight:300; color:var(--muted); line-height:1.75; letter-spacing:0.02em; }

/* ARTIST PAGE */
.artist-sec { padding:5rem 2rem 7rem; max-width:1100px; margin:0 auto; }
.artist-inner { display:flex; gap:5rem; align-items:flex-start; margin-top:1rem; }
.artist-portrait-col { flex-shrink:0; }
.artist-portrait-frame {
  width:260px; height:320px;
  border:1px solid var(--border);
  box-shadow:0 0 0 6px var(--surface),0 0 0 7px var(--border),0 35px 80px rgba(0,0,0,0.8);
  overflow:hidden; position:relative;
}
.artist-portrait-placeholder {
  width:100%; height:100%; background:var(--surface2);
  display:flex; align-items:center; justify-content:center; cursor:pointer; transition:background 0.3s;
}
.artist-portrait-placeholder:hover { background:var(--surface); }
.artist-portrait-placeholder svg { width:80px; height:80px; opacity:0.4; }
.artist-portrait-placeholder img { width:100%; height:100%; object-fit:cover; display:block; }
.artist-portrait-hint { font-size:0.58rem; letter-spacing:0.25em; text-transform:uppercase; color:var(--muted); margin-top:0.9rem; text-align:center; opacity:0.6; }
.artist-text-col { flex:1; }
.about-text { font-size:1.05rem; font-weight:300; color:var(--muted); line-height:2.1; letter-spacing:0.03em; }

/* CONTACT */
.contact-sec { padding:5rem 2rem 8rem; max-width:900px; margin:0 auto; }
.contact-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(200px,1fr)); gap:2.5rem 3rem; margin-top:1rem; }
.contact-item { display:flex; flex-direction:column; align-items:center; text-align:center; gap:0.7rem; }
.contact-icon { width:48px; height:48px; border:1px solid var(--border); display:flex; align-items:center; justify-content:center; color:var(--gold); }
.contact-icon svg { width:20px; height:20px; }
.contact-label { font-size:0.6rem; letter-spacing:0.45em; text-transform:uppercase; color:var(--muted); }
.contact-value { font-size:0.95rem; color:var(--text); text-decoration:none; letter-spacing:0.04em; transition:color 0.3s; font-style:italic; }
.contact-value:hover { color:var(--gold); }

/* FOOTER */
.main-footer { border-top:1px solid var(--border); padding:3.5rem 4rem; display:flex; justify-content:space-between; align-items:center; }
.foot-logo { font-family:'Cinzel',serif; font-size:1rem; letter-spacing:0.35em; color:var(--gold); }
.foot-text { font-size:0.7rem; letter-spacing:0.15em; color:var(--muted); }
.admin-btn { font-size:0.6rem; letter-spacing:0.2em; text-transform:uppercase; color:transparent; cursor:pointer; background:none; border:none; font-family:inherit; transition:color 0.3s; }
.admin-btn:hover { color:var(--muted); }

/* LIGHTBOX */
.lightbox { position:fixed; inset:0; z-index:700; display:flex; align-items:center; justify-content:center; opacity:0; pointer-events:none; transition:opacity 0.4s; }
.lightbox.open { opacity:1; pointer-events:all; }
.lb-bg { position:absolute; inset:0; background:rgba(7,7,6,0.96); backdrop-filter:blur(12px); cursor:pointer; }
.lb-close { position:absolute; top:2rem; right:2.5rem; z-index:1; background:none; border:1px solid var(--border); color:var(--muted); width:42px; height:42px; cursor:pointer; font-size:1.1rem; display:flex; align-items:center; justify-content:center; transition:all 0.25s; }
.lb-close:hover { color:var(--gold); border-color:var(--gold); }
.lb-content { position:relative; z-index:1; display:flex; flex-direction:column; align-items:center; gap:1.8rem; transform:scale(0.88); transition:transform 0.4s; max-width:85vw; max-height:90vh; }
.lightbox.open .lb-content { transform:scale(1); }
.lb-content img { max-width:100%; max-height:72vh; object-fit:contain; }
.lb-title { font-size:1.55rem; font-style:italic; letter-spacing:0.05em; color:var(--text); }

/* PASSWORD MODAL */
.pw-modal { position:fixed; inset:0; z-index:800; display:flex; align-items:center; justify-content:center; background:rgba(7,7,6,0.96); opacity:0; pointer-events:none; transition:opacity 0.3s; }
.pw-modal.open { opacity:1; pointer-events:all; }
.pw-box { border:1px solid var(--border); padding:3.5rem 4.5rem; text-align:center; max-width:400px; width:90%; background:var(--surface); }
.pw-title { font-family:'Cinzel',serif; font-size:0.8rem; letter-spacing:0.45em; color:var(--gold); margin-bottom:2.5rem; }
.pw-input { background:transparent; border:none; border-bottom:1px solid var(--border); color:var(--text); font-family:'Cormorant Garamond',serif; font-size:1.3rem; padding:0.5rem 1rem; text-align:center; width:100%; outline:none; letter-spacing:0.3em; margin-bottom:2.2rem; transition:border-color 0.2s; }
.pw-input:focus { border-bottom-color:var(--gold); }
.pw-submit { background:transparent; border:1px solid var(--gold); color:var(--gold); font-family:'Cormorant Garamond',serif; font-size:0.72rem; letter-spacing:0.45em; text-transform:uppercase; padding:0.8rem 2.5rem; cursor:pointer; transition:all 0.3s; }
.pw-submit:hover { background:var(--gold); color:var(--black); }
.pw-err { font-size:0.72rem; color:rgba(220,80,80,0.8); margin-top:1rem; letter-spacing:0.12em; min-height:1rem; }

/* OWNER PANEL */
.panel-overlay { position:fixed; inset:0; z-index:600; background:rgba(7,7,6,0.65); backdrop-filter:blur(4px); opacity:0; pointer-events:none; transition:opacity 0.4s; }
.panel-overlay.open { opacity:1; pointer-events:all; }
.owner-panel { position:fixed; top:0; right:0; bottom:0; width:min(580px,96vw); background:var(--surface); border-left:1px solid var(--border); z-index:601; overflow-y:auto; transform:translateX(102%); transition:transform 0.5s cubic-bezier(0.25,0.46,0.45,0.94); display:flex; flex-direction:column; }
.owner-panel.open { transform:translateX(0); }
.panel-head { padding:1.8rem 1.8rem 1.4rem; border-bottom:1px solid var(--border); display:flex; justify-content:space-between; align-items:center; position:sticky; top:0; background:var(--surface); z-index:1; }
.panel-head-title { font-family:'Cinzel',serif; font-size:0.78rem; letter-spacing:0.38em; color:var(--gold); }
.panel-x { background:none; border:1px solid var(--border); color:var(--muted); width:34px; height:34px; cursor:pointer; font-size:1rem; display:flex; align-items:center; justify-content:center; transition:all 0.2s; }
.panel-x:hover { color:var(--gold); border-color:var(--gold); }
.panel-body { padding:1.5rem 1.8rem 3rem; flex:1; }

/* GALLERY SETTINGS */
.settings-toggle { width:100%; padding:0.8rem 1rem; background:transparent; border:1px solid var(--border); color:var(--muted); font-family:'Cormorant Garamond',serif; font-size:0.78rem; letter-spacing:0.3em; text-transform:uppercase; cursor:pointer; text-align:left; display:flex; justify-content:space-between; align-items:center; transition:all 0.2s; margin-bottom:0.8rem; }
.settings-toggle:hover { border-color:var(--gold); color:var(--gold); }
.settings-body { display:none; padding:1.2rem; border:1px solid var(--border); border-top:none; margin-bottom:1.5rem; background:rgba(255,255,255,0.02); }
.settings-body.open { display:block; }
.settings-row { margin-bottom:1rem; }
.settings-label { font-size:0.62rem; letter-spacing:0.3em; text-transform:uppercase; color:var(--gold); margin-bottom:0.35rem; display:block; }
.settings-input { background:transparent; border:none; border-bottom:1px solid var(--border); color:var(--text); font-family:'Cormorant Garamond',serif; font-size:1rem; padding:0.3rem 0; width:100%; outline:none; transition:border-color 0.2s; }
.settings-input:focus { border-bottom-color:var(--gold); }
.settings-textarea { background:transparent; border:1px solid var(--border); color:var(--text); font-family:'Cormorant Garamond',serif; font-size:0.9rem; padding:0.6rem; width:100%; outline:none; resize:vertical; min-height:70px; transition:border-color 0.2s; }
.settings-textarea:focus { border-color:var(--gold); }

/* ADD BUTTON */
.add-btn { width:100%; padding:0.9rem; background:transparent; border:1px dashed var(--border); color:var(--gold); font-family:'Cormorant Garamond',serif; font-size:0.78rem; letter-spacing:0.35em; text-transform:uppercase; cursor:pointer; transition:all 0.3s; margin-bottom:1.8rem; }
.add-btn:hover { border-color:var(--gold); background:rgba(200,169,81,0.05); }

/* PAINTING EDIT ITEM */
.p-edit { background:rgba(255,255,255,0.025); border:1px solid var(--border); margin-bottom:1.3rem; padding:1.1rem; position:relative; transition:border-color 0.3s; }
.p-edit:hover { border-color:rgba(200,169,81,0.35); }
.p-edit-num { position:absolute; top:0.7rem; right:0.8rem; font-size:0.6rem; letter-spacing:0.2em; color:var(--muted); }
.p-edit-top { display:flex; gap:0.9rem; align-items:flex-start; margin-bottom:1rem; }
.thumb-wrap { width:88px; height:68px; flex-shrink:0; position:relative; cursor:pointer; border:1px solid var(--border); overflow:hidden; transition:border-color 0.2s; }
.thumb-wrap img { width:100%; height:100%; object-fit:cover; display:block; }
.thumb-wrap .thumb-overlay { position:absolute; inset:0; background:rgba(0,0,0,0.7); display:flex; flex-direction:column; align-items:center; justify-content:center; opacity:0; transition:opacity 0.2s; font-size:0.6rem; letter-spacing:0.15em; color:var(--gold); gap:0.2rem; }
.thumb-wrap .thumb-overlay svg { width:18px; height:18px; opacity:0.8; }
.thumb-wrap:hover .thumb-overlay, .thumb-wrap.drag-over .thumb-overlay { opacity:1; }
.thumb-wrap.drag-over { border-color:var(--gold); box-shadow:0 0 0 2px rgba(200,169,81,0.3); }
.p-edit-fields { flex:1; display:flex; flex-direction:column; gap:0.45rem; }
.e-input { background:transparent; border:none; border-bottom:1px solid var(--border); color:var(--text); font-family:'Cormorant Garamond',serif; font-size:0.95rem; padding:0.35rem 0; width:100%; outline:none; transition:border-color 0.2s; }
.e-input:focus { border-bottom-color:var(--gold); }
.e-input::placeholder { color:var(--muted); font-style:italic; }
.e-textarea { background:transparent; border:1px solid var(--border); color:var(--text); font-family:'Cormorant Garamond',serif; font-size:0.85rem; padding:0.55rem; width:100%; outline:none; resize:vertical; min-height:56px; margin-bottom:0.75rem; transition:border-color 0.2s; }
.e-textarea:focus { border-color:var(--gold); }
.e-textarea::placeholder { color:var(--muted); font-style:italic; }
.frame-sel { display:flex; gap:0.4rem; flex-wrap:wrap; margin-bottom:0.75rem; align-items:center; }
.frame-sel-label { font-size:0.6rem; letter-spacing:0.2em; text-transform:uppercase; color:var(--muted); margin-right:0.1rem; }
.f-opt { padding:0.28rem 0.6rem; font-size:0.62rem; letter-spacing:0.12em; text-transform:uppercase; border:1px solid var(--border); background:transparent; color:var(--muted); cursor:pointer; transition:all 0.2s; font-family:'Cormorant Garamond',serif; }
.f-opt:hover, .f-opt.active { border-color:var(--gold); color:var(--gold); background:rgba(200,169,81,0.07); }
.p-edit-foot { display:flex; justify-content:space-between; align-items:center; }
.p-edit-hint { font-size:0.6rem; color:var(--muted); letter-spacing:0.08em; }
.p-move { display:flex; gap:0.3rem; }
.move-btn { background:none; border:1px solid var(--border); color:var(--muted); width:26px; height:26px; cursor:pointer; font-size:0.75rem; display:flex; align-items:center; justify-content:center; transition:all 0.2s; }
.move-btn:hover { color:var(--gold); border-color:var(--gold); }
.del-btn { background:none; border:1px solid rgba(180,60,60,0.3); color:rgba(220,100,100,0.6); padding:0.28rem 0.7rem; font-size:0.6rem; letter-spacing:0.2em; text-transform:uppercase; cursor:pointer; font-family:'Cormorant Garamond',serif; transition:all 0.2s; }
.del-btn:hover { border-color:rgba(220,80,80,0.6); color:rgba(230,80,80,0.9); }

/* FLOATING LOCK BUTTON */
.lock-btn {
  position: fixed;
  bottom: 2rem;
  right: 2rem;
  z-index: 500;
  width: 48px;
  height: 48px;
  background: var(--surface);
  border: 1px solid var(--border);
  color: var(--muted);
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.3s;
  box-shadow: 0 4px 24px rgba(0,0,0,0.5);
}
.lock-btn:hover { border-color: var(--gold); color: var(--gold); box-shadow: 0 4px 24px rgba(200,169,81,0.15); }
.lock-btn svg { width: 18px; height: 18px; }
.lock-btn .lock-label {
  position: absolute;
  right: 56px;
  background: var(--surface);
  border: 1px solid var(--border);
  color: var(--muted);
  font-size: 0.6rem;
  letter-spacing: 0.25em;
  text-transform: uppercase;
  padding: 0.3rem 0.7rem;
  white-space: nowrap;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.2s;
}
.lock-btn:hover .lock-label { opacity: 1; }

/* PW CHANGE SECTION */
.pw-change-section { margin-top: 2rem; border-top: 1px solid var(--border); padding-top: 1.5rem; }
.pw-change-title { font-size: 0.62rem; letter-spacing: 0.35em; text-transform: uppercase; color: var(--muted); margin-bottom: 1rem; }
.pw-change-row { display: flex; gap: 0.5rem; align-items: center; }
.pw-change-input { background: transparent; border: none; border-bottom: 1px solid var(--border); color: var(--text); font-family: 'Cormorant Garamond', serif; font-size: 0.95rem; padding: 0.3rem 0.4rem; flex: 1; outline: none; transition: border-color 0.2s; }
.pw-change-input:focus { border-bottom-color: var(--gold); }
.pw-change-input::placeholder { color: var(--muted); font-style: italic; }
.pw-change-btn { background: transparent; border: 1px solid var(--border); color: var(--muted); font-family: 'Cormorant Garamond', serif; font-size: 0.65rem; letter-spacing: 0.25em; text-transform: uppercase; padding: 0.4rem 0.9rem; cursor: pointer; transition: all 0.2s; white-space: nowrap; }
.pw-change-btn:hover { border-color: var(--gold); color: var(--gold); }
.pw-change-ok { font-size: 0.65rem; color: rgba(100,200,100,0.8); letter-spacing: 0.1em; margin-top: 0.4rem; min-height: 1rem; }

/* HAMBURGER */
.nav-hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  cursor: pointer;
  padding: 4px;
  background: none;
  border: none;
  z-index: 300;
}
.nav-hamburger span {
  display: block;
  width: 24px;
  height: 1.5px;
  background: var(--muted);
  transition: all 0.35s ease;
  transform-origin: center;
}
.nav-hamburger.open span:nth-child(1) { transform: translateY(6.5px) rotate(45deg); background: var(--gold); }
.nav-hamburger.open span:nth-child(2) { opacity: 0; transform: scaleX(0); }
.nav-hamburger.open span:nth-child(3) { transform: translateY(-6.5px) rotate(-45deg); background: var(--gold); }

/* MOBILE NAV DRAWER */
.nav-drawer {
  position: fixed;
  top: 0; right: 0; bottom: 0;
  width: min(280px, 85vw);
  background: rgba(10,9,8,0.98);
  backdrop-filter: blur(20px);
  border-left: 1px solid var(--border);
  z-index: 250;
  transform: translateX(102%);
  transition: transform 0.4s cubic-bezier(0.25,0.46,0.45,0.94);
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 3rem 2.5rem;
  gap: 0.5rem;
}
.nav-drawer.open { transform: translateX(0); }
.nav-drawer a {
  font-size: 1.4rem;
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-weight: 300;
  color: var(--muted);
  text-decoration: none;
  letter-spacing: 0.06em;
  padding: 0.9rem 0;
  border-bottom: 1px solid var(--border);
  transition: color 0.3s;
  display: block;
}
.nav-drawer a:last-child { border-bottom: none; }
.nav-drawer a:hover { color: var(--gold); }
.nav-overlay {
  position: fixed; inset: 0;
  z-index: 249;
  background: rgba(0,0,0,0.5);
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.4s;
}
.nav-overlay.open { opacity: 1; pointer-events: all; }

/* TOAST */
.toast { position:fixed; bottom:2rem; left:50%; transform:translateX(-50%) translateY(16px); background:var(--surface); border:1px solid var(--gold); color:var(--gold); padding:0.65rem 2rem; font-size:0.65rem; letter-spacing:0.35em; text-transform:uppercase; opacity:0; transition:all 0.4s; pointer-events:none; z-index:9998; }
.toast.show { opacity:1; transform:translateX(-50%) translateY(0); }

/* ── RESPONSIVE ─────────────────────────────── */
@media(max-width:768px){
  /* Nav */
  nav { padding: 1.2rem 1.5rem; }
  .nav-links { display: none; }
  .nav-hamburger { display: flex; }

  /* Hero */
  .hero-title { font-size: clamp(3rem, 16vw, 6rem); }
  .hero-subtitle { font-size: 0.85rem; letter-spacing: 0.14em; padding: 0 1rem; }
  .hero-eyebrow { font-size: 0.6rem; }

  /* Gallery */
  .gallery-wrap { padding: 0 1.2rem 5rem; }
  .gallery-grid { grid-template-columns: 1fr; gap: 3rem; }
  .sec-head { padding: 5rem 1.5rem 3rem; }

  /* Artist */
  .artist-sec { padding: 3rem 1.5rem 5rem; }
  .artist-inner { flex-direction: column; gap: 2rem; align-items: center; }
  .artist-portrait-frame { width: 180px; height: 220px; }
  .artist-text-col { text-align: center; }
  .about-text { font-size: 0.98rem; line-height: 1.95; }

  /* Contact */
  .contact-sec { padding: 3rem 1.5rem 5rem; }
  .contact-grid { grid-template-columns: 1fr 1fr; gap: 2rem 1.5rem; }
  .contact-value { font-size: 0.85rem; word-break: break-all; }

  /* Footer */
  .main-footer { flex-direction: column; gap: 1rem; text-align: center; padding: 2.5rem 1.5rem; }

  /* Lightbox */
  .lb-content { max-width: 95vw; }

  /* Lock button */
  .lock-btn { bottom: 1.2rem; right: 1.2rem; }

  /* Owner panel */
  .owner-panel { width: 96vw; }

  /* pw-change-row stacked */
  .pw-change-row { flex-wrap: wrap; }
}

@media(max-width:420px){
  .contact-grid { grid-template-columns: 1fr; }
  .artist-portrait-frame { width: 150px; height: 185px; }
  .hero-title { font-size: clamp(2.6rem, 18vw, 5rem); }
}
</style>
</head>
<body>

<nav id="main-nav">
  <div class="nav-logo" id="site-name-display">ATELIER</div>
  <ul class="nav-links">
    <li><a href="#about">Künstler</a></li>
    <li><a href="#contact">Kontakt</a></li>
  </ul>
  <button class="nav-hamburger" id="nav-hamburger" aria-label="Menü öffnen">
    <span></span><span></span><span></span>
  </button>
</nav>

<!-- Mobile Nav Overlay + Drawer -->
<div class="nav-overlay" id="nav-overlay"></div>
<div class="nav-drawer" id="nav-drawer">
  <a href="#about" class="drawer-link">Künstler</a>
  <a href="#contact" class="drawer-link">Kontakt</a>
</div>

<section class="hero">
  <div class="hero-bg"></div>
  <canvas id="particles-canvas"></canvas>
  <div class="hero-eyebrow" id="hero-eye-display">Galerie — Wien, 2025</div>
  <h1 class="hero-title" id="hero-title-display">Die <em>Stille</em><br>des Lichts</h1>
  <p class="hero-subtitle" id="hero-sub-display">Eine Ausstellung zeitgenössischer Gemälde</p>
  <div class="hero-rule"></div>
  <div class="hero-scroll"><span>Scrollen</span><div class="scroll-bar"></div></div>
</section>

<section id="gallery">
  <div class="sec-head">
    <div class="sec-eye">Kollektion</div>
    <h2 class="sec-title">Die Werke</h2>
    <div class="sec-line"></div>
  </div>
  <div class="gallery-wrap">
    <div class="gallery-grid" id="gallery-grid"></div>
  </div>
</section>

<section id="about" class="artist-sec">
  <div class="sec-head">
    <div class="sec-eye">Der Künstler</div>
    <h2 class="sec-title" id="about-name-display">Über mich</h2>
    <div class="sec-line"></div>
  </div>
  <div class="artist-inner">
    <div class="artist-portrait-col">
      <div class="artist-portrait-frame">
        <div class="artist-portrait-placeholder" id="artist-portrait-wrap">
          <svg viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="40" cy="30" r="18" stroke="rgba(200,169,81,0.4)" stroke-width="1.2"/>
            <path d="M10 72c0-16.569 13.431-30 30-30s30 13.431 30 30" stroke="rgba(200,169,81,0.4)" stroke-width="1.2"/>
          </svg>
        </div>
      </div>
    </div>
    <div class="artist-text-col">
      <p class="about-text" id="about-text-display">Jedes Gemälde entsteht aus dem Moment — aus der Begegnung von Licht, Stille und Bewegung. Meine Arbeiten suchen den Raum zwischen dem Sichtbaren und dem Gefühlten, zwischen dem Greifbaren und dem, was sich der Sprache entzieht.</p>
      <p class="about-text" id="about-text2-display" style="margin-top:1.4rem;"></p>
    </div>
  </div>
</section>

<section id="contact" class="contact-sec">
  <div class="sec-head">
    <div class="sec-eye">Kontakt</div>
    <h2 class="sec-title">Erreichen Sie mich</h2>
    <div class="sec-line"></div>
  </div>
  <div class="contact-grid">
    <div class="contact-item" id="contact-phone-wrap">
      <div class="contact-icon">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.81a19.79 19.79 0 01-3.07-8.68A2 2 0 012 0h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L6.09 7.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z"/></svg>
      </div>
      <div class="contact-label">Telefon</div>
      <a class="contact-value" id="contact-phone-link" href="#"><span id="contact-phone-display">—</span></a>
    </div>
    <div class="contact-item" id="contact-email-wrap">
      <div class="contact-icon">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
      </div>
      <div class="contact-label">E-Mail</div>
      <a class="contact-value" id="contact-email-link" href="#"><span id="contact-email-display">—</span></a>
    </div>
    <div class="contact-item" id="contact-instagram-wrap">
      <div class="contact-icon">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37z"/><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"/></svg>
      </div>
      <div class="contact-label">Instagram</div>
      <a class="contact-value" id="contact-instagram-link" href="#" target="_blank"><span id="contact-instagram-display">—</span></a>
    </div>
    <div class="contact-item" id="contact-facebook-wrap">
      <div class="contact-icon">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"/></svg>
      </div>
      <div class="contact-label">Facebook</div>
      <a class="contact-value" id="contact-facebook-link" href="#" target="_blank"><span id="contact-facebook-display">—</span></a>
    </div>
  </div>
</section>

<footer class="main-footer">
  <div class="foot-logo" id="foot-name-display">ATELIER</div>
  <div class="foot-text">© 2025 — Alle Rechte vorbehalten</div>
</footer>

<!-- LIGHTBOX -->
<div class="lightbox" id="lightbox">
  <div class="lb-bg" id="lb-bg"></div>
  <button class="lb-close" id="lb-close">✕</button>
  <div class="lb-content">
    <img id="lb-img" src="" alt="">
    <div class="lb-title" id="lb-title"></div>
  </div>
</div>

<!-- FLOATING LOCK BUTTON -->
<button class="lock-btn" id="admin-trigger" title="Owner-Zugang">
  <span class="lock-label">Owner-Bereich</span>
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
    <rect x="3" y="11" width="18" height="11" rx="2" ry="2"/>
    <path d="M7 11V7a5 5 0 0 1 10 0v4"/>
  </svg>
</button>

<!-- PASSWORD -->
<div class="pw-modal" id="pw-modal">
  <div class="pw-box">
    <div class="pw-title">Owner — Zugang</div>
    <input type="password" class="pw-input" id="pw-input" placeholder="Passwort">
    <br>
    <button class="pw-submit" id="pw-ok">Eintreten</button>
    <div class="pw-err" id="pw-err"></div>
  </div>
</div>

<!-- OWNER PANEL -->
<div class="panel-overlay" id="panel-overlay"></div>
<div class="owner-panel" id="owner-panel">
  <div class="panel-head">
    <div class="panel-head-title">Galerie Verwalten</div>
    <button class="panel-x" id="panel-close">✕</button>
  </div>
  <div class="panel-body">

    <!-- SETTINGS -->
    <button class="settings-toggle" id="settings-toggle">
      <span>⚙ Galerie-Einstellungen</span>
      <span id="settings-arrow">▼</span>
    </button>
    <div class="settings-body" id="settings-body">
      <div class="settings-row">
        <label class="settings-label">Name / Logo</label>
        <input class="settings-input" id="set-name" placeholder="z.B. ATELIER">
      </div>
      <div class="settings-row">
        <label class="settings-label">Hero — Eyebrow-Text</label>
        <input class="settings-input" id="set-eye" placeholder="z.B. Galerie — Wien, 2025">
      </div>
      <div class="settings-row">
        <label class="settings-label">Hero — Haupttitel (HTML erlaubt für &lt;em&gt;Kursiv&lt;/em&gt;)</label>
        <input class="settings-input" id="set-title" placeholder="Die &lt;em&gt;Stille&lt;/em&gt;&lt;br&gt;des Lichts">
      </div>
      <div class="settings-row">
        <label class="settings-label">Hero — Untertitel</label>
        <input class="settings-input" id="set-sub" placeholder="Eine Ausstellung…">
      </div>
      <div class="settings-row">
        <label class="settings-label">Über den Künstler — Name/Titel</label>
        <input class="settings-input" id="set-about-name" placeholder="Über mich">
      </div>
      <div class="settings-row">
        <label class="settings-label">Über den Künstler — Text</label>
        <textarea class="settings-textarea" id="set-about-text" rows="3" placeholder="Biografie…"></textarea>
      </div>
      <div class="settings-row">
        <label class="settings-label">Über den Künstler — Zweiter Absatz (optional)</label>
        <textarea class="settings-textarea" id="set-about-text2" rows="3" placeholder="Weiterer Text…"></textarea>
      </div>
      <div class="settings-row" style="margin-top:1.5rem;border-top:1px solid var(--border);padding-top:1.2rem;">
        <label class="settings-label" style="color:var(--gold-l);margin-bottom:0.8rem;display:block;">📞 Kontakt-Informationen</label>
      </div>
      <div class="settings-row">
        <label class="settings-label">Telefonnummer</label>
        <input class="settings-input" id="set-contact-phone" placeholder="z.B. +43 123 456 789">
      </div>
      <div class="settings-row">
        <label class="settings-label">E-Mail-Adresse</label>
        <input class="settings-input" id="set-contact-email" placeholder="z.B. name@email.com">
      </div>
      <div class="settings-row">
        <label class="settings-label">Instagram (nur Username)</label>
        <input class="settings-input" id="set-contact-instagram" placeholder="z.B. kuenstler_name">
      </div>
      <div class="settings-row">
        <label class="settings-label">Facebook (Username oder Seiten-Name)</label>
        <input class="settings-input" id="set-contact-facebook" placeholder="z.B. MeineKunstseite">
      </div>
      <div class="pw-change-section">
        <div class="pw-change-title">🔒 Passwort ändern</div>
        <div class="pw-change-row">
          <input type="password" class="pw-change-input" id="pw-new" placeholder="Neues Passwort">
          <input type="password" class="pw-change-input" id="pw-new2" placeholder="Wiederholen">
          <button class="pw-change-btn" id="pw-change-btn">Speichern</button>
        </div>
        <div class="pw-change-ok" id="pw-change-ok"></div>
      </div>
    </div>

    <button class="add-btn" id="add-btn">+ Neues Gemälde hinzufügen</button>
    <div id="paintings-list"></div>
  </div>
</div>

<div class="toast" id="toast">Gespeichert</div>

<script>
// ───────────────────────────────────────────────
// CONSTANTS
// ───────────────────────────────────────────────
const PWD_DEFAULT = 'artist2025';
let currentPwd = PWD_DEFAULT;
const FRAME_OPTS = [
  {v:'frame-ornate-gold', l:'Gold'},
  {v:'frame-modern-black', l:'Modern'},
  {v:'frame-rustic-wood', l:'Holz'},
  {v:'frame-silver', l:'Silber'},
  {v:'frame-white', l:'Weiß'},
  {v:'frame-none', l:'Kein'},
];

// ───────────────────────────────────────────────
// STATE
// ───────────────────────────────────────────────
let paintings = [];
let settings = {
  name: 'ATELIER',
  heroEye: 'Galerie — Wien, 2025',
  heroTitle: 'Die <em>Stille</em><br>des Lichts',
  heroSub: 'Eine Ausstellung zeitgenössischer Gemälde',
  aboutName: 'Über mich',
  aboutText: 'Jedes Gemälde entsteht aus dem Moment — aus der Begegnung von Licht, Stille und Bewegung. Meine Arbeiten suchen den Raum zwischen dem Sichtbaren und dem Gefühlten, zwischen dem Greifbaren und dem, was sich der Sprache entzieht.',
  aboutText2: '',
  contactPhone: '',
  contactEmail: '',
  contactInstagram: '',
  contactFacebook: '',
};
let nextId = 10;

// ───────────────────────────────────────────────
// PLACEHOLDER GENERATION
// ───────────────────────────────────────────────
function genPlaceholder(idx) {
  const c = document.createElement('canvas'); c.width=800; c.height=600;
  const ctx = c.getContext('2d');
  const palettes = [
    ['#0f0800','#2d1500','#7a3c0a','#c87840','#f0c898'],
    ['#04040f','#0d0d30','#283278','#5568b8','#b0c0f0'],
    ['#020a04','#083010','#1e6830','#48a060','#a8d8b0'],
    ['#0d0108','#2a0318','#7a1038','#b84070','#f0a0c0'],
    ['#090600','#261c00','#7a5610','#c89838','#f0d888'],
    ['#010c10','#022030','#0a5068','#2888a8','#90c8e0'],
  ];
  const pal = palettes[idx % palettes.length];
  const gr = ctx.createRadialGradient(400,280,0,400,280,560);
  gr.addColorStop(0,pal[2]); gr.addColorStop(0.5,pal[1]); gr.addColorStop(1,pal[0]);
  ctx.fillStyle=gr; ctx.fillRect(0,0,800,600);
  for(let i=0;i<18;i++){
    ctx.save(); ctx.translate(Math.random()*800,Math.random()*600); ctx.rotate(Math.random()*Math.PI*2);
    ctx.globalAlpha=0.12+Math.random()*0.28;
    const ig=ctx.createRadialGradient(0,0,0,0,0,80+Math.random()*220);
    ig.addColorStop(0,pal[3+Math.floor(Math.random()*2)]); ig.addColorStop(1,'transparent');
    ctx.fillStyle=ig; ctx.beginPath(); ctx.ellipse(0,0,80+Math.random()*220,40+Math.random()*160,0,0,Math.PI*2); ctx.fill(); ctx.restore();
  }
  const lg=ctx.createRadialGradient(350+Math.random()*150,180+Math.random()*80,0,400,300,420);
  lg.addColorStop(0,'rgba(255,240,200,0.22)'); lg.addColorStop(1,'transparent');
  ctx.fillStyle=lg; ctx.fillRect(0,0,800,600);
  ctx.globalAlpha=0.1;
  for(let i=0;i<60;i++){
    ctx.strokeStyle=pal[Math.floor(Math.random()*pal.length)];
    ctx.lineWidth=0.8+Math.random()*2.5; ctx.beginPath();
    ctx.moveTo(Math.random()*800,Math.random()*600);
    ctx.bezierCurveTo(Math.random()*800,Math.random()*600,Math.random()*800,Math.random()*600,Math.random()*800,Math.random()*600);
    ctx.stroke();
  }
  return c.toDataURL('image/jpeg',0.85);
}

// ───────────────────────────────────────────────
// DEFAULTS
// ───────────────────────────────────────────────
function getDefaults() {
  const d = [
    {title:'Goldener Abend', year:'2024', description:'Das Licht verfängt sich im letzten Moment des Tages — eine Stille, die atmet.', frame:'frame-ornate-gold'},
    {title:'Dämmerung über Wien', year:'2023', description:'Die Stadt erwacht unter einem violetten Himmel, der alles in Traum verwandelt.', frame:'frame-ornate-gold'},
    {title:'Stilles Wasser', year:'2024', description:'Reflektionen, die tiefer reichen als die Oberfläche.', frame:'frame-modern-black'},
    {title:'Herbstlicher Garten', year:'2022', description:'Das Verblühen als Schönheit — jeder Blatt ein Abschiedsgruß.', frame:'frame-rustic-wood'},
    {title:'Mondnacht', year:'2023', description:'Der Mond malt mit Licht, was der Tag verborgen hielt.', frame:'frame-silver'},
    {title:'Erwachen', year:'2025', description:'Das erste Licht trifft auf das Dunkel — der Moment zwischen Schlaf und Welt.', frame:'frame-ornate-gold'},
  ];
  return d.map((x,i)=>({id:i+1,...x, imageData:genPlaceholder(i)}));
}

// ───────────────────────────────────────────────
// STORAGE
// ───────────────────────────────────────────────
function load() {
  try {
    const p = localStorage.getItem('gallery_v2_paintings');
    const s = localStorage.getItem('gallery_v2_settings');
    if(p){ const d=JSON.parse(p); paintings=d.list||[]; nextId=d.nid||(paintings.length+10); }
    if(s){ settings={...settings,...JSON.parse(s)}; }
    const pw=localStorage.getItem('gallery_v2_pwd'); if(pw) currentPwd=pw;
    return !!p;
  } catch(e){ return false; }
}
function save() {
  try {
    localStorage.setItem('gallery_v2_paintings', JSON.stringify({list:paintings,nid:nextId}));
    localStorage.setItem('gallery_v2_settings', JSON.stringify(settings));
    showToast();
  } catch(e) {
    if(e.name==='QuotaExceededError') alert('Speicher voll. Bitte verkleinern Sie die Bilder.');
  }
}
function showToast() {
  const t=document.getElementById('toast'); t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'),2200);
}

// ───────────────────────────────────────────────
// APPLY SETTINGS
// ───────────────────────────────────────────────
function applySettings() {
  document.getElementById('site-name-display').textContent=settings.name||'ATELIER';
  document.getElementById('foot-name-display').textContent=settings.name||'ATELIER';
  document.getElementById('hero-eye-display').textContent=settings.heroEye||'';
  document.getElementById('hero-title-display').innerHTML=settings.heroTitle||'';
  document.getElementById('hero-sub-display').textContent=settings.heroSub||'';
  document.getElementById('about-name-display').textContent=settings.aboutName||'Über mich';
  document.getElementById('about-text-display').textContent=settings.aboutText||'';
  document.getElementById('about-text2-display').textContent=settings.aboutText2||'';
  document.title=(settings.name||'Atelier')+' — Kunstgalerie';
  // Contact
  const phone=settings.contactPhone||'';
  document.getElementById('contact-phone-display').textContent=phone||'—';
  document.getElementById('contact-phone-link').href=phone?'tel:'+phone.replace(/\s/g,''):'#';
  document.getElementById('contact-phone-wrap').style.opacity=phone?'1':'0.35';
  const email=settings.contactEmail||'';
  document.getElementById('contact-email-display').textContent=email||'—';
  document.getElementById('contact-email-link').href=email?'mailto:'+email:'#';
  document.getElementById('contact-email-wrap').style.opacity=email?'1':'0.35';
  const ig=settings.contactInstagram||'';
  document.getElementById('contact-instagram-display').textContent=ig?('@'+ig.replace(/^@/,'')):'—';
  document.getElementById('contact-instagram-link').href=ig?'https://instagram.com/'+ig.replace(/^@/,''):'#';
  document.getElementById('contact-instagram-wrap').style.opacity=ig?'1':'0.35';
  const fb=settings.contactFacebook||'';
  document.getElementById('contact-facebook-display').textContent=fb||'—';
  document.getElementById('contact-facebook-link').href=fb?('https://facebook.com/'+fb.replace(/^https?:\/\/(www\.)?facebook\.com\//,'')):'#';
  document.getElementById('contact-facebook-wrap').style.opacity=fb?'1':'0.35';
}

// ───────────────────────────────────────────────
// GALLERY RENDER
// ───────────────────────────────────────────────
function renderGallery() {
  const grid=document.getElementById('gallery-grid');
  grid.innerHTML='';
  paintings.forEach((p,i)=>{
    const card=document.createElement('div');
    card.className='pcard';
    card.style.transitionDelay=`${(i%3)*0.15}s`;
    card.innerHTML=`
      <div class="p-wrapper ${p.frame||'frame-ornate-gold'}" data-id="${p.id}">
        <div class="p-img-box">
          <img src="${p.imageData}" alt="${escHtml(p.title||'')}" loading="lazy">
          <div class="p-spot"></div>
          <div class="p-overlay"><span class="p-overlay-title">${escHtml(p.title||'')}</span></div>
        </div>
      </div>
      <div class="p-info">
        <div class="p-meta">
          <div class="p-title">${escHtml(p.title||'')}</div>
          <div class="p-year">${escHtml(p.year||'')}</div>
        </div>
        <div class="p-desc">${escHtml(p.description||'')}</div>
      </div>`;
    const wrap=card.querySelector('.p-wrapper');
    const spot=card.querySelector('.p-spot');
    wrap.addEventListener('mousemove',e=>{
      const r=wrap.getBoundingClientRect();
      const x=((e.clientX-r.left)/r.width)*100;
      const y=((e.clientY-r.top)/r.height)*100;
      spot.style.background=`radial-gradient(circle 190px at ${x}% ${y}%,rgba(255,255,200,0.15),transparent 70%)`;
    });
    wrap.addEventListener('click',()=>openLB(p));
    grid.appendChild(card);
  });
  setupScroll();
}
function escHtml(s){ const d=document.createElement('div'); d.textContent=s; return d.innerHTML; }

// ───────────────────────────────────────────────
// LIGHTBOX
// ───────────────────────────────────────────────
function openLB(p) {
  document.getElementById('lb-img').src=p.imageData;
  document.getElementById('lb-title').textContent=p.title||'';
  document.getElementById('lightbox').classList.add('open');
}
function closeLB(){ document.getElementById('lightbox').classList.remove('open'); }
document.getElementById('lb-close').onclick=closeLB;
document.getElementById('lb-bg').onclick=closeLB;
document.addEventListener('keydown',e=>{ if(e.key==='Escape'){ closeLB(); closePWModal(); } });

// ───────────────────────────────────────────────
// SCROLL ANIMATIONS
// ───────────────────────────────────────────────
function setupScroll() {
  const obs=new IntersectionObserver(entries=>{
    entries.forEach(en=>{ if(en.isIntersecting){ en.target.classList.add('visible'); obs.unobserve(en.target); }});
  },{threshold:0.08});
  document.querySelectorAll('.pcard').forEach(el=>obs.observe(el));
}

// ───────────────────────────────────────────────
// NAV SCROLL
// ───────────────────────────────────────────────
window.addEventListener('scroll',()=>{
  document.getElementById('main-nav').classList.toggle('scrolled',window.scrollY>60);
});

// ───────────────────────────────────────────────
// PARTICLES
// ───────────────────────────────────────────────
function initParticles() {
  const cv=document.getElementById('particles-canvas');
  const ctx=cv.getContext('2d');
  const resize=()=>{ cv.width=window.innerWidth; cv.height=window.innerHeight; };
  resize(); window.addEventListener('resize',resize);
  const pts=Array.from({length:55},()=>({
    x:Math.random()*window.innerWidth, y:Math.random()*window.innerHeight,
    vx:(Math.random()-.5)*0.25, vy:-Math.random()*0.35-.08,
    sz:Math.random()*1.8+0.4, a:Math.random()*0.35+0.08, life:Math.random()
  }));
  function frame(){
    ctx.clearRect(0,0,cv.width,cv.height);
    pts.forEach(p=>{
      p.x+=p.vx; p.y+=p.vy; p.life+=0.0025;
      if(p.y<-8||p.life>1){ p.x=Math.random()*cv.width; p.y=cv.height+8; p.life=0; }
      const al=p.a*Math.sin(p.life*Math.PI);
      ctx.beginPath(); ctx.arc(p.x,p.y,p.sz,0,Math.PI*2);
      ctx.fillStyle=`rgba(200,169,81,${al.toFixed(3)})`; ctx.fill();
    });
    requestAnimationFrame(frame);
  }
  frame();
}

// ───────────────────────────────────────────────
// PASSWORD
// ───────────────────────────────────────────────
document.getElementById('admin-trigger').onclick=()=>{
  document.getElementById('pw-modal').classList.add('open');
  setTimeout(()=>document.getElementById('pw-input').focus(),100);
};
function closePWModal(){ document.getElementById('pw-modal').classList.remove('open'); document.getElementById('pw-input').value=''; document.getElementById('pw-err').textContent=''; }
function checkPW(){
  const v=document.getElementById('pw-input').value;
  if(v===currentPwd){ closePWModal(); openOwnerPanel(); }
  else { document.getElementById('pw-err').textContent='Falsches Passwort'; document.getElementById('pw-input').value=''; }
}
document.getElementById('pw-ok').onclick=checkPW;
document.getElementById('pw-input').addEventListener('keydown',e=>{ if(e.key==='Enter')checkPW(); if(e.key==='Escape')closePWModal(); });

// ───────────────────────────────────────────────
// OWNER PANEL
// ───────────────────────────────────────────────
function openOwnerPanel(){ renderOwnerPanel(); fillSettings(); document.getElementById('owner-panel').classList.add('open'); document.getElementById('panel-overlay').classList.add('open'); }
function closeOwnerPanel(){ document.getElementById('owner-panel').classList.remove('open'); document.getElementById('panel-overlay').classList.remove('open'); }
document.getElementById('panel-close').onclick=closeOwnerPanel;
document.getElementById('panel-overlay').onclick=closeOwnerPanel;

// Settings toggle
document.getElementById('settings-toggle').onclick=()=>{
  const b=document.getElementById('settings-body'); const a=document.getElementById('settings-arrow');
  b.classList.toggle('open'); a.textContent=b.classList.contains('open')?'▲':'▼';
};

function fillSettings(){
  document.getElementById('set-name').value=settings.name||'';
  document.getElementById('set-eye').value=settings.heroEye||'';
  document.getElementById('set-title').value=settings.heroTitle||'';
  document.getElementById('set-sub').value=settings.heroSub||'';
  document.getElementById('set-about-name').value=settings.aboutName||'';
  document.getElementById('set-about-text').value=settings.aboutText||'';
  document.getElementById('set-about-text2').value=settings.aboutText2||'';
  document.getElementById('set-contact-phone').value=settings.contactPhone||'';
  document.getElementById('set-contact-email').value=settings.contactEmail||'';
  document.getElementById('set-contact-instagram').value=settings.contactInstagram||'';
  document.getElementById('set-contact-facebook').value=settings.contactFacebook||'';
}
function bindSettings(){
  const fields=[
    ['set-name','name'],['set-eye','heroEye'],['set-title','heroTitle'],
    ['set-sub','heroSub'],['set-about-name','aboutName'],['set-about-text','aboutText'],
    ['set-about-text2','aboutText2'],
    ['set-contact-phone','contactPhone'],['set-contact-email','contactEmail'],
    ['set-contact-instagram','contactInstagram'],['set-contact-facebook','contactFacebook']
  ];
  fields.forEach(([id,key])=>{
    const el=document.getElementById(id);
    el.oninput=()=>{ settings[key]=el.value; applySettings(); save(); };
  });
  document.getElementById('pw-change-btn').onclick=()=>{
    const n1=document.getElementById('pw-new').value.trim();
    const n2=document.getElementById('pw-new2').value.trim();
    const ok=document.getElementById('pw-change-ok');
    if(!n1){ ok.style.color='rgba(220,80,80,0.8)'; ok.textContent='Bitte ein Passwort eingeben.'; return; }
    if(n1!==n2){ ok.style.color='rgba(220,80,80,0.8)'; ok.textContent='Passwörter stimmen nicht überein.'; return; }
    currentPwd=n1;
    localStorage.setItem('gallery_v2_pwd', currentPwd);
    document.getElementById('pw-new').value='';
    document.getElementById('pw-new2').value='';
    ok.style.color='rgba(100,200,100,0.8)';
    ok.textContent='✓ Passwort gespeichert!';
    setTimeout(()=>ok.textContent='', 3000);
  };
}

// ───────────────────────────────────────────────
// OWNER PANEL RENDER
// ───────────────────────────────────────────────
function renderOwnerPanel(){
  const list=document.getElementById('paintings-list');
  list.innerHTML='';
  paintings.forEach((p,idx)=>{
    const item=document.createElement('div');
    item.className='p-edit'; item.dataset.id=p.id;
    item.innerHTML=`
      <div class="p-edit-num">#${idx+1}</div>
      <div class="p-edit-top">
        <div class="thumb-wrap" id="tw-${p.id}">
          <img src="${p.imageData}" alt="">
          <div class="thumb-overlay">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4M17 8l-5-5-5 5M12 3v12"/></svg>
            <span>Bild ersetzen</span>
          </div>
        </div>
        <div class="p-edit-fields">
          <input class="e-input" type="text" placeholder="Titel" value="${escHtml(p.title||'')}">
          <input class="e-input" type="text" placeholder="Jahr (z.B. 2024)" value="${escHtml(p.year||'')}">
        </div>
      </div>
      <textarea class="e-textarea" placeholder="Beschreibung…">${escHtml(p.description||'')}</textarea>
      <div class="frame-sel">
        <span class="frame-sel-label">Rahmen:</span>
        ${FRAME_OPTS.map(f=>`<button class="f-opt${p.frame===f.v?' active':''}" data-frame="${f.v}">${f.l}</button>`).join('')}
      </div>
      <div class="p-edit-foot">
        <div class="p-move">
          <button class="move-btn" data-dir="-1" title="Nach oben">↑</button>
          <button class="move-btn" data-dir="1" title="Nach unten">↓</button>
        </div>
        <span class="p-edit-hint">Klicken oder Drag&amp;Drop zum Ersetzen</span>
        <button class="del-btn">✕ Löschen</button>
      </div>`;
    // Input bindings
    const inputs=item.querySelectorAll('.e-input');
    inputs[0].onchange=()=>updateF(p.id,'title',inputs[0].value);
    inputs[1].onchange=()=>updateF(p.id,'year',inputs[1].value);
    item.querySelector('.e-textarea').onchange=(e)=>updateF(p.id,'description',e.target.value);
    // Frame buttons
    item.querySelectorAll('.f-opt').forEach(btn=>{ btn.onclick=()=>updateF(p.id,'frame',btn.dataset.frame); });
    // Move
    item.querySelectorAll('.move-btn').forEach(btn=>{ btn.onclick=()=>movePainting(p.id,parseInt(btn.dataset.dir)); });
    // Delete
    item.querySelector('.del-btn').onclick=()=>deletePainting(p.id);
    // Thumb drop
    setupThumbDrop(item.querySelector('.thumb-wrap'),p.id);
    list.appendChild(item);
  });
}

function setupThumbDrop(tw,id){
  tw.addEventListener('click',()=>{
    const inp=document.createElement('input'); inp.type='file'; inp.accept='image/*';
    inp.onchange=e=>{ const f=e.target.files[0]; if(f) readImg(f,id); }; inp.click();
  });
  tw.addEventListener('dragover',e=>{ e.preventDefault(); tw.classList.add('drag-over'); });
  tw.addEventListener('dragleave',()=>tw.classList.remove('drag-over'));
  tw.addEventListener('drop',e=>{
    e.preventDefault(); tw.classList.remove('drag-over');
    const f=e.dataTransfer.files[0]; if(f&&f.type.startsWith('image/')) readImg(f,id);
  });
}
function readImg(file,id){
  const r=new FileReader(); r.onload=e=>{ updateF(id,'imageData',e.target.result); }; r.readAsDataURL(file);
}
function updateF(id,field,val){
  const p=paintings.find(x=>x.id===id); if(!p) return;
  p[field]=val; applySettings(); renderGallery(); save(); renderOwnerPanel();
}
function movePainting(id,dir){
  const i=paintings.findIndex(p=>p.id===id); const ni=i+dir;
  if(ni<0||ni>=paintings.length) return;
  [paintings[i],paintings[ni]]=[paintings[ni],paintings[i]];
  renderGallery(); save(); renderOwnerPanel();
}
function deletePainting(id){
  if(!confirm('Gemälde wirklich löschen?')) return;
  paintings=paintings.filter(p=>p.id!==id); renderGallery(); save(); renderOwnerPanel();
}
document.getElementById('add-btn').onclick=()=>{
  const np={ id:nextId++, title:'Neues Gemälde', year:new Date().getFullYear()+'', description:'', frame:'frame-ornate-gold', imageData:genPlaceholder(paintings.length) };
  paintings.push(np); renderGallery(); save(); renderOwnerPanel();
  setTimeout(()=>{ const l=document.getElementById('paintings-list'); l.lastElementChild?.scrollIntoView({behavior:'smooth',block:'nearest'}); },120);
};

// ───────────────────────────────────────────────
// INIT
// ───────────────────────────────────────────────
function init(){
  const ok=load();
  if(!ok||paintings.length===0){ paintings=getDefaults(); nextId=20; save(); }
  applySettings();
  renderGallery();
  initParticles();
  bindSettings();
}
// ───────────────────────────────────────────────
// MOBILE NAV
// ───────────────────────────────────────────────
(function(){
  const burger = document.getElementById('nav-hamburger');
  const drawer = document.getElementById('nav-drawer');
  const overlay = document.getElementById('nav-overlay');
  function openNav(){ burger.classList.add('open'); drawer.classList.add('open'); overlay.classList.add('open'); document.body.style.overflow='hidden'; }
  function closeNav(){ burger.classList.remove('open'); drawer.classList.remove('open'); overlay.classList.remove('open'); document.body.style.overflow=''; }
  burger.addEventListener('click', ()=> drawer.classList.contains('open') ? closeNav() : openNav());
  overlay.addEventListener('click', closeNav);
  document.querySelectorAll('.drawer-link').forEach(a => a.addEventListener('click', closeNav));
})();

init();
</script>
</body>
</html>
