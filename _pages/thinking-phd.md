 ---
 layout: single
 title: "Thinking PhD?"
 permalink: /thinking-phd/
 author_profile: true
 ---
 
 **Thinking about a PhD? You're not alone.**
 
-<p>
-    Download my <a href="/files/phd_guide.pdf">PhD Application Guide (PDF)</a>.
-</p>
+<p>
+  Download my
+  <a href="{{ '/files/phd_guide.pdf' | relative_url }}" download>
+    PhD Application Guide (PDF)
+  </a>.
+</p>
+
+<style>
+  /* Responsive PDF embed */
+  .pdf-container {
+    margin: 1rem 0;
+    /* Use the smaller of 80% viewport height or 900px */
+    height: min(80vh, 900px);
+    max-width: 100%;
+    border: 1px solid rgba(0,0,0,0.08);
+    border-radius: 8px;
+    overflow: hidden;
+    box-shadow: 0 1px 8px rgba(0,0,0,0.06);
+  }
+  .pdf-container iframe,
+  .pdf-container object {
+    width: 100%;
+    height: 100%;
+    border: 0;
+    display: block;
+  }
+  /* Mobile: shrink or hide the heavy preview */
+  @media (max-width: 768px) {
+    .pdf-container {
+      height: 60vh;           /* or switch to display:none; to hide entirely */
+    }
+  }
+</style>
+
+<div class="pdf-container">
+  <object
+    data="{{ '/files/phd_guide.pdf' | relative_url }}"
+    type="application/pdf">
+      <p>
+        Your browser can’t display embedded PDFs.
+        <a href="{{ '/files/phd_guide.pdf' | relative_url }}" target="_blank" rel="noopener">
+          Open the PDF in a new tab
+        </a>.
+      </p>
+  </object>
+</div>
 
 The creation of this website, along with my advice document to prospective PhD students, was heavily inspired by resources found on [Emma Megla](https://www.emmamegla.com/home)'s website.
 
 Feel free to reach out — I’m always happy to answer questions or review materials when I can.
 
 > brecken@uchicago.edu
