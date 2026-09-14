# Simple Guide to Creating Product Advertising Images with AI

**hajimohtava.ai**

────────────────────────────────────────

This guide teaches you how to create 9 professional advertising images from a single simple photo of your product. You don't need any prior knowledge — just follow the steps.

────────────────────────────────────────

## Step 1: What Do You Need?

────────────────────────────────────────

1. A clear photo of your product (you can take it with your phone; just make sure the lighting is good and the background isn't cluttered).

2. Access to one of these two tools (both can be used for free):

* ChatGPT
* Gemini (which also includes Nano Banana)

────────────────────────────────────────

## Step 2: Upload Your Product Photo

────────────────────────────────────────

Open ChatGPT or Gemini. You'll see a paperclip button or a **+** icon next to the message box. Click it and upload your product photo.

────────────────────────────────────────

## Step 3: Prepare the Prompt

────────────────────────────────────────

At the bottom of this guide, you'll find a long English text called a **"prompt."** Copy it.

Inside this text, you'll see several words enclosed in **[ ]**, like this:

`[PRODUCT_NAME]`

These mean **"write something of your own here."** You need to replace these placeholders with information about your product. The table below explains exactly what each one means and gives you a real example.

────────────────────────────────────────

## Step 4: Variable Guide — What Should I Replace Them With?

────────────────────────────────────────

### 1) `[GRID_LINE_COLOR]`

**What is it?** The color of the thin lines separating the 9 images.

**Example:** `white`

### 2) `[PRODUCT_NAME]`

**What is it?** The exact name of your product.

**Example:** `Rosewood Matte Lipstick`

### 3) `[BRAND_PRIMARY_COLOR]`

**What is it?** The main color of your brand or product packaging.

**Example:** `dark red`

### 4) `[BRAND_SECONDARY_COLOR]`

**What is it?** A secondary color used in your product packaging.

**Example:** `gold`

### 5) `[SURFACE_MATERIAL]`

**What is it?** The surface the product will be placed on.

**Example:** `white marble`

### 6) `[SPECIFIC_SURFACE_FEATURE]`

**What is it?** The specific part of the product you want to show as an extreme close-up.

**Example:** `the logo on the cap`

### 7) `[SHAPE_TYPES]`

**What is it?** A few simple geometric shapes placed next to the product for decoration.

**Example:** `a sphere and a cylinder`

### 8) `[MATERIAL]`

**What is it?** The material the geometric shapes are made of.

**Example:** `white plaster`

### 9) `[SUPPORTING_ELEMENTS]`

**What is it?** Small elements that appear floating around the product.

**Example:** `flower petals`

### 10) `[SPECIFIC_TACTILE_DETAIL]`

**What is it?** The physical texture or tactile quality of the product you want to highlight.

**Example:** `a shiny reflective surface`

### 11) `[DOMINANT_PRODUCT_COLOR]`

**What is it?** The dominant color of the product itself — not its packaging.

**Example:** `deep red`

### 12) `[KEY_INGREDIENT_OR_COMPONENT]`

**What is it?** The most important ingredient or component of the product.

**Example:** `rose petals`

**Important:** In the prompt, there is a section called **"Cell 3"** that has no placeholders to fill in. Leave it exactly as it is. The AI will understand what to do automatically.

────────────────────────────────────────

## Step 5: How Do I Fill In the Placeholders? (Complete Example)

────────────────────────────────────────

Let's say your product is a red lipstick.

Whenever you see:

`[PRODUCT_NAME]`

Delete it and write:

`Rosewood Matte Lipstick`

Do the same for all 12 placeholders. Once you've filled in all of them, copy the entire prompt and send it together with your product photo to ChatGPT or Gemini.

────────────────────────────────────────

## Step 6: Wait for the Image to Be Generated

────────────────────────────────────────

After you send the prompt, it may take anywhere from a few seconds to a few minutes. You'll receive one large image made up of 9 sections — each showing a different angle or creative concept featuring the same product.

────────────────────────────────────────

## Step 7: Check That Everything Looks Correct

────────────────────────────────────────

Check these 4 things:

✓ The product looks exactly the same in all 9 images (colors, text, and logo have not changed).

✓ The lighting is consistent across all images.

✓ The product hasn't become distorted or misshapen.

✓ The product edges are clean against the background, with no color bleeding, halo, or unwanted artifacts.

If one of these isn't correct, don't worry — simply send the same prompt again. The second generation will usually be better.

────────────────────────────────────────

# Main Prompt (Copy This Entire Prompt)

────────────────────────────────────────

Create a single image containing a 3x3 grid layout (9 equal cells, 3 columns × 3 rows, thin uniform [GRID_LINE_COLOR] separator lines between cells), overall canvas in 3:4 aspect ratio.

**PRODUCT (identity-locked across all 9 cells):**

The product shown in the uploaded reference image is [PRODUCT_NAME]. Use this exact reference for shape, proportions, label text, typography, logo placement, color values, cap/lid design, and material finish. Do not alter, redesign, restyle, or reinterpret the product in any cell — including in Cell 7 and Cell 9. The product itself must look photographed, not illustrated or stylized, in every single cell.

**CONSISTENCY LOCK (applies to all 9 cells):**

* Camera-to-product distance and product scale stay within the same relative range across cells (no cell should make the product look like a different size relative to frame)

* Studio lighting setup: single soft key light from upper-left at roughly 45°, fill light at 20% intensity from the right, no colored gels

* Color temperature: 5600K neutral daylight balance in every cell

* Background palette across all 9 cells must share the same limited palette derived from [BRAND_PRIMARY_COLOR] and [BRAND_SECONDARY_COLOR] — no cell introduces an unrelated hue

* Shadow direction stays consistent (soft shadow falling to the lower-right in every cell)

**CELL-BY-CELL DIRECTION:**

**Cell 1 — Hero Still Life:**

Product centered, three-quarter angle, resting on a [SURFACE_MATERIAL] surface, single soft shadow beneath, negative space above for potential headline placement. Sharp focus on the entire product, background softly out of focus.

**Cell 2 — Extreme Macro Detail:**

Camera pushed to within a few centimeters of the product surface, showing [SPECIFIC_SURFACE_FEATURE]. Shallow depth of field, only a narrow focal plane sharp, rest falls into soft blur. No full product silhouette visible — this is a texture-level detail shot.

**Cell 3 — Dynamic Material Interaction:**

Identify the product's own core material or defining sensory trait from the reference image (e.g. if liquid-based: the liquid itself; if solid/dry: fine particles matching its actual texture — powder, dust, fragments, droplets of condensation, or shavings — whatever is physically native to that specific product, not an unrelated substance).

Show that native material captured mid-motion in a frozen-action moment — either erupting/splashing upward around the product, orbiting it in a dynamic radial burst, or cascading past it — using a shutter-speed-frozen look (crisp edges on every droplet/particle, zero motion blur, like a high-speed strobe capture).

Material color must be pulled directly from the product's own real-world color or ingredient (not an arbitrary contrasting color).

Product itself stays perfectly still, sharp, and physically untouched by the motion — the energy exists only in the surrounding material, never deforming or splashing onto the product's readable label/branding area.

Composition: product placed slightly off-center (rule-of-thirds), material interaction fills the opposite third of the frame for dynamic tension.

**Cell 4 — Minimal Sculptural Arrangement:**

Product paired with 2–3 abstract geometric solid shapes ([SHAPE_TYPES] in [MATERIAL]) arranged in a balanced asymmetric composition. Negative space dominates the frame.

**Cell 5 — Floating Elements:**

Product appears to hover slightly above the surface (subtle motion-implied shadow beneath confirming it's airborne, not edited-out). [SUPPORTING_ELEMENTS] suspended mid-air around it, all elements sharp, implying weightlessness rather than a jump/throw.

**Cell 6 — Sensory Close-Up:**

Tight crop emphasizing tactility — [SPECIFIC_TACTILE_DETAIL]. Focus on making the surface feel touchable; realistic micro-imperfections visible (not overly smoothed/plastic-looking).

**Cell 7 — Color-Driven Conceptual Scene:**

CRITICAL EXCEPTION: this monochromatic rule applies ONLY to the background/environment — every element that is NOT the product itself. The product's actual label colors, cap color, and branding colors must remain 100% identical to the reference image, completely unaffected by the scene's color wash. The product keeps its true original colors even while surrounded by a monochromatic environment.

Full-frame color wash derived directly from [DOMINANT_PRODUCT_COLOR], product placed off-center within a monochromatic environment of that same hue family, creating a tonal, editorial-color-story frame.

Contrast rule: the background must be a lower-saturation, lower-contrast tint/shade of [DOMINANT_PRODUCT_COLOR], while the product itself keeps its full saturation and true value — separation comes from value and saturation contrast within the same hue family, never from introducing a different hue.

**Cell 8 — Ingredient/Component Abstraction:**

Symbolic, non-literal representation of [KEY_INGREDIENT_OR_COMPONENT] arranged near (not merged into) the product — e.g. raw material fragments, powder, botanical elements — kept visually separate from the product body itself so the product silhouette stays 100% unaltered.

**Cell 9 — Elegant Realism-Fusion Scene:**

A stylized environment or backdrop (e.g. dreamlike lighting, unexpected but physically plausible setting) surrounds the product — the SCENE may be imaginative, but the product itself remains photographically literal and unaltered, exactly as in the reference image. No morphing, blending, or merging of the product's form with any element in the scene.

**TECHNICAL SPEC (applies globally):**

8K resolution equivalent detail, ultra-sharp focus on product in every cell, high dynamic range, no motion blur on the product itself, no visible text/watermarks, no distortion of proportions in any cell, clean product-to-background edge separation (no color bleed/halo).

────────────────────────────────────────

© hajimohtava.ai
