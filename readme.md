
# Struttura del progetto

## SRC
* |-- app
   * |-- core
     * |-- [+] animations
     * |-- [+] guards
     * |-- [+] resolvers
     * |-- [+] models
     * |-- [+] helpers
     * |-- [+] http (basic http calls)
     * |-- [+] interceptors
     * |-- [+] services
     * |-- [+] components
     * |-- [+] ngrx
     * |-- core.module.ts
   * |-- modules
     * |-- home (**home** è un placeholder per il nome_modulo)
       * |-- [+] components
       * |-- [+] pages
       * |-- [+] ngrx
       * |-- home-routing.module.ts
       * |-- home.module.ts
       * |-- [+] modules (se è necessario nestare moduli)
   * |-- utils
   * |-- shared
     * |-- [+] components
     * |-- [+] directives
     * |-- [+] pipes
* |-- assets
  * |-- [+] js
  * |-- [+] imgs
  * |-- [+] bgs
  * |-- [+] icons
* |-- styles
  * |-- [+] partials
  * |-- styles.scss
