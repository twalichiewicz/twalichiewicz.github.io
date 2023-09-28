---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: none
---

<html lang="en">
	<head>
		<link
			rel="apple-touch-icon"
			sizes="180x180"
			href="/media/apple-touch-icon.png"
		/>
		<link
			rel="icon"
			type="image/png"
			sizes="32x32"
			href="/media/favicon-32x32.png"
		/>
		<link
			rel="icon"
			type="image/png"
			sizes="16x16"
			href="/media/favicon-16x16.png"
		/>
		<link rel="manifest" href="/media/site.webmanifest" />
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<title>Thomas Walichiewicz - Digital Product Designer</title>
		<link rel="stylesheet" type="text/css" href="/src/styles/index.css" />
		<script src="https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.18.0/matter.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/two.js@v0.7.0-stable.1/build/two.js"></script>
    </head>
    <body>
    	<div class="interactiveStuff" style="display: flex;align-items: end;position: absolute; text-align: left;width: 100%; z-index: 999;padding: 21px;left:0;right:0;margin-left:auto;margin-right:auto;top:0;bottom:0;margin-top:-3px;margin-bottom:auto;height:fit-content;border-radius: 0 0 12px 12px;max-width:fit-content;border: solid 1px rgba(0,0,0,0.2);">
            <h1 style="margin: 0;font-size: 6vw;font-family: sans-serif;line-height:84%;font-weight:100;margin-right:9px;">THOMAS<br/>DESIGN</h1>
            <div class="spacer" style="flex: 1;"></div>
            <div class="row">
                <a class="" href="https://www.thomas.design/blog/">
                    <div class="cube link">
                        <svg
                            clip-rule="evenodd"
                            fill-rule="evenodd"
                            height="18"
                            stroke-linejoin="round"
                            stroke-miterlimit="2"
                            viewBox="0 0 24 24"
                            width="18"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="m2.699 20c-.411 0-.699-.312-.699-.662 0-.249.145-.516.497-.703 1.788-.947 3.858-4.226 3.858-6.248-3.016.092-4.326-2.582-4.326-4.258 0-2.006 1.738-4.129 4.308-4.129 3.241 0 4.83 2.547 4.83 5.307 0 5.981-6.834 10.693-8.468 10.693zm10.833 0c-.41 0-.699-.312-.699-.662 0-.249.145-.516.497-.703 1.788-.947 3.858-4.226 3.858-6.248-3.015.092-4.326-2.582-4.326-4.258 0-2.006 1.739-4.129 4.308-4.129 3.241 0 4.83 2.547 4.83 5.307 0 5.981-6.833 10.693-8.468 10.693z"
                                fill-rule="nonzero"
                            />
                        </svg>
                        <span>Blog</span>
                    </div>
                </a>
                <a class="" href="https://www.thomas.design/portfolio/">
                    <div class="cube link">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="18"
                            height="18"
                            viewBox="0 0 24 24"
                        >
                            <path
                                d="M9 6h-2v-2c0-1.104.896-2 2-2h6c1.104 0 2 .896 2 2v2h-2v-1.5c0-.276-.224-.5-.5-.5h-5c-.276 0-.5.224-.5.5v1.5zm7 6v2h8v8h-24v-8h8v-2h-8v-5h24v5h-8zm-2-1h-4v4h4v-4z"
                            />
                        </svg>
                        <span>Portfolio</span>
                    </div></a
                ><a class="" href="mailto:hey@thomas.design"
                    ><div class="cube link">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="18"
                            height="18"
                            viewBox="0 0 24 24"
                        >
                            <path
                                d="M24 0l-6 22-8.129-7.239 7.802-8.234-10.458 7.227-7.215-1.754 24-12zm-15 16.668v7.332l3.258-4.431-3.258-2.901z"
                            />
                        </svg>
                        <span>Email</span>
                    </div></a
                ><a class="" href="https://www.linkedin.com/in/twalichiewicz"
                    ><div class="cube link">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="18"
                            height="18"
                            viewBox="0 0 24 24"
                        >
                            <path
                                d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                            />
                        </svg>
                        <span>LinkedIn</span>
                    </div>
                </a>
            </div>
            <div style="position:absolute;background: rgba(255,255,255,0.96);filter: blur(1px);box-shadow: 0 12px 24px rgba(0,0,0,0.12);top:0;bottom:0;left:0;right:0;z-index:-1;border-radius: 12px;"></div>
        </div>
        <script>
          var vector = new Two.Vector();
          var entities = [];
          var mouse;
          var copy = [
            "Coding",
            "Branding",
            "Research",
            "Testing",
            "Strategy",
            "Analytics",
            "Guidance",
            "MVP",
            "Product Design",
            "Visual Design",
            "Roadmap",
            "UX",
            "Analysis",
            "Prototyping",
          ];

          var two = new Two({
            type: Two.Types.canvas,
            fullscreen: true,
            autostart: true
          }).appendTo(document.body);

          var solver = Matter.Engine.create();
          solver.world.gravity.y = 1;

          var bounds = {
            length: 5000,
            thickness: 50,
            properties: {
              isStatic: true
            }
          };

          // bounds.top = createBoundary(bounds.length, bounds.thickness);
          bounds.left = createBoundary(bounds.thickness, bounds.length);
          bounds.right = createBoundary(bounds.thickness, bounds.length);
          bounds.bottom = createBoundary(bounds.length, bounds.thickness);

          Matter.World.add(solver.world, [
            /*bounds.top.entity,*/ bounds.left.entity,
            bounds.right.entity,
            bounds.bottom.entity
          ]);

          var defaultStyles = {
            size: two.width * 0.08,
            weight: 600,
            fill: "black",
            leading: two.width * 0.08 * 0.8,
            family: "Inter, sans-serif",
            alignment: "center",
            baseline: "baseline",
            margin: {
              top: 0,
              left: 0,
              right: 0,
              bottom: 0
            }
          };

          addSlogan();
          resize();
          mouse = addMouseInteraction();
          two.bind("resize", resize).bind("update", update);

          function addMouseInteraction() {
            // add mouse control
            var mouse = Matter.Mouse.create(document.body);
            var mouseConstraint = Matter.MouseConstraint.create(solver, {
              mouse: mouse,
              constraint: {
                stiffness: 0.2
              }
            });

            Matter.World.add(solver.world, mouseConstraint);

            return mouseConstraint;
          }

          function resize() {
            var length = bounds.length;
            var thickness = bounds.thickness;

            // vector.x = two.width / 2;
            // vector.y = - thickness / 2;
            // Matter.Body.setPosition(bounds.top.entity, vector);

            vector.x = -thickness / 2;
            vector.y = two.height / 2;
            Matter.Body.setPosition(bounds.left.entity, vector);

            vector.x = two.width + thickness / 2;
            vector.y = two.height / 2;
            Matter.Body.setPosition(bounds.right.entity, vector);

            vector.x = two.width / 2;
            vector.y = two.height + thickness / 2;
            Matter.Body.setPosition(bounds.bottom.entity, vector);

            var size;

            if (two.width < 480) {
              size = two.width * 0.12;
            } else if (two.width > 1080 && two.width < 1600) {
              size = two.width * 0.07;
            } else if (two.width > 1600) {
              size = two.width * 0.06;
            } else {
              size = two.width * 0.08;
            }

            var leading = size * 0.8;

            for (var i = 0; i < two.scene.children.length; i++) {
              var child = two.scene.children[i];

              if (!child.isWord) {
                continue;
              }

              var text = child.text;
              var rectangle = child.rectangle;
              var entity = child.entity;

              text.size = size;
              text.leading = leading;

              var rect = text.getBoundingClientRect(true);
              rectangle.width = rect.width;
              rectangle.height = rect.height;

              Matter.Body.scale(entity, 1 / entity.scale.x, 1 / entity.scale.y);
              Matter.Body.scale(entity, rect.width, rect.height);
              entity.scale.set(rect.width, rect.height);

              text.size = size / 1;
            }
          }

          function addSlogan() {
            var x = defaultStyles.margin.left;
            var y = -two.height; // Header offset

            for (var i = 0; i < copy.length; i++) {
              var word = copy[i];
              var group = new Two.Group();
              var text = new Two.Text("", 0, 0, defaultStyles);

              group.isWord = true;

              // Override default styles
              if (word.value) {
                text.value = word.value;

                for (var prop in word.styles) {
                  text[prop] = word.styles[prop];
                }
              } else {
                text.value = word;
              }

              var rect = text.getBoundingClientRect();
              var ox = x + rect.width / 2;
              var oy = y + rect.height / 2;

              var ca = x + rect.width;
              var cb = two.width;

              // New line
              if (ca >= cb) {
                x = defaultStyles.margin.left;
                y +=
                  defaultStyles.leading +
                  defaultStyles.margin.top +
                  defaultStyles.margin.bottom;

                ox = x + rect.width / 2;
                oy = y + rect.height / 2;
              }

              group.translation.x = ox;
              group.translation.y = oy;
              text.translation.y = 14;

              var rectangle = new Two.Rectangle(0, 0, rect.width, rect.height);
              // rectangle.fill = 'rgb(255, 50, 50)';
              rectangle.fill =
                "transparent";
              rectangle.noStroke();
              // rectangle.opacity = 0.75;
              rectangle.visible = true;

              var entity = Matter.Bodies.rectangle(ox, oy, 1, 1);
              Matter.Body.scale(entity, rect.width, rect.height);

              entity.scale = new Two.Vector(rect.width, rect.height);
              entity.object = group;
              entities.push(entity);

              x += rect.width + defaultStyles.margin.left + defaultStyles.margin.right;

              group.text = text;
              group.rectangle = rectangle;
              group.entity = entity;

              group.add(rectangle, text);
              two.add(group);
            }

            Matter.World.add(solver.world, entities);
          }

          function update(frameCount, timeDelta) {
            var allBodies = Matter.Composite.allBodies(solver.world);
            Matter.MouseConstraint.update(mouse, allBodies);
            Matter.MouseConstraint._triggerEvents(mouse);

            Matter.Engine.update(solver);

            for (var i = 0; i < entities.length; i++) {
              var entity = entities[i];
              entity.object.position.copy(entity.position);
              entity.object.rotation = entity.angle;
            }
          }

          function createBoundary(width, height) {
            var rectangle = two.makeRectangle(0, 0, width, height);
            rectangle.visible = false;

            rectangle.entity = Matter.Bodies.rectangle(
              0,
              0,
              width,
              height,
              bounds.properties
            );
            rectangle.entity.position = rectangle.position;

            return rectangle;
          }
    	</script>
    </body>

</html>
