* { box-sizing: border-box; }
html { margin: 0; padding: 0; background: #fff; }
body { margin: 0; padding: 0; background: #fff; }
.portfolio { width: 100%; }
.portfolio-page {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  background: #fff;
  overflow: hidden;
}
.portfolio-page img {
  display: block;
  width: 100%;
  height: auto;
  max-width: 1536px;
  aspect-ratio: 4 / 3;
  object-fit: contain;
}
@media (min-width: 1537px) {
  .portfolio-page { padding: 0; }
}
@media (max-width: 700px) {
  .portfolio-page img { width: 100vw; max-width: none; }
}
