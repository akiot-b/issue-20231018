# Content v2 Minimal Starter

nuxt no longer requires 'shamefully-hoist=true' in workspace+pnpm as of 3.7.4.
Currently, @nuxt/content warns without 'shamefully-hoist'.

[pnpm support without --shamefully-hoist #14146](https://github.com/nuxt/nuxt/issues/14146#issuecomment-1767243568)

By the way, if you use npm, you will not get any warning.

## Usage

```bash
pnpm install
cd nuxt
pnpm dev
```

```bash
 WARN  Failed to resolve dependency: slugify, present in 'optimizeDeps.include'      
 WARN  Failed to resolve dependency: is-buffer, present in 'optimizeDeps.include'    
 WARN  Failed to resolve dependency: debug, present in 'optimizeDeps.include'        
 WARN  Failed to resolve dependency: flat, present in 'optimizeDeps.include'         
 WARN  Failed to resolve dependency: node-emoji, present in 'optimizeDeps.include'   
 WARN  Failed to resolve dependency: extend, present in 'optimizeDeps.include'       
 WARN  Failed to resolve dependency: hast-util-raw, present in 'optimizeDeps.include'   
```
