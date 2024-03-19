# Frontend Api Performance

Project was moved to Vite

## Optimizations done

1. Added minification usign terser (Apparently better than esbuild)
2. Use defer on scripts
3. Used imagemin & cssnano in vite config
4. Put loading="lazy" on all images (for index.html for now)
