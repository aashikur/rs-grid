# rs-grid
.rs-grid {
    display: grid !important;
    grid-template-columns: auto;
}
 @media only screen and (min-width: 768px) {
      .rs-grid {
       grid-template-columns: auto auto;
    }
}
 @media only screen and (min-width: 1024px) {
      .rs-grid {
       grid-template-columns: auto auto auto;
    }
}
