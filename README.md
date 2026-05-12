# Clarvix Limpeza de Vidros — Site Institucional

Site estático em HTML + CSS puro para a **Clarvix Limpeza de Vidros**, empresa de limpeza profissional de vidros residenciais, comerciais e pós-obra, sediada em São Pedro – SP.

---

## 📁 Estrutura de arquivos

```
clarvix-site/
├── index.html                    # Página principal
├── sobre.html                    # Sobre a empresa
├── contato.html                  # Contato e canais
├── orcamento.html                # Como solicitar orçamento
├── faq.html                      # Perguntas frequentes
├── galeria.html                  # Galeria de serviços
├── sitemap.html                  # Mapa visual do site
├── 404.html                      # Página de erro
│
├── residencial.html              # Serviço residencial
├── comercial.html                # Serviço comercial
├── pos-obra.html                 # Serviço pós-obra
│
├── sao-pedro.html                # SEO local — São Pedro
├── aguas-de-sao-pedro.html       # SEO local — Águas de São Pedro
├── charqueada.html               # SEO local — Charqueada
├── piracicaba.html               # SEO local — Piracicaba
├── santa-maria-da-serra.html     # SEO local — Santa Maria da Serra
├── brotas.html                   # SEO local — Brotas
├── ipeuna.html                   # SEO local — Ipeúna
├── rio-claro.html                # SEO local — Rio Claro
│
├── sitemap.xml                   # Sitemap técnico para Google
├── robots.txt                    # Instruções para crawlers
├── llms.txt                      # Versão estruturada para IAs
├── og-image.png                  # Imagem Open Graph (1200×630)
└── .gitignore
```

## ✅ Checklist técnico

- HTML semântico com hierarquia H1 → H2 → H3 → H4
- 1 único H1 por página com palavra-chave principal
- Meta title, description, canonical e robots em todas as páginas
- Open Graph + Twitter Card com og-image.png
- Schema JSON-LD: LocalBusiness, FAQPage, BreadcrumbList
- Skip link de acessibilidade em todas as páginas
- `rel="noopener noreferrer"` em todos os links externos
- WhatsApp com mensagem pré-preenchida em todos os botões
- `loading="lazy"` em imagens não críticas
- Responsivo mobile-first

## 🌐 Publicação

1. Subir arquivos na raiz do domínio
2. Configurar `ErrorDocument 404 /404.html` no servidor
3. Adicionar headers de segurança (ver recomendações em llms.txt)
4. Submeter `sitemap.xml` no Google Search Console
5. Atualizar URLs canônicas de `https://www.clarvix.com.br` para o domínio real

## 📞 Contato

- WhatsApp: (11) 99952-8805
- E-mail: clarvixvidros@gmail.com
- Instagram: @clarvix.vidros
