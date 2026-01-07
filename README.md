Stick Fix – Pre‑order Website
· typescript
import { Button } from "@/components/ui/button";
            Pre‑Order Now
          </Button>
          <Button
            size="lg"
            variant="outline"
            className="rounded-2xl px-8"
          >
            Learn More
          </Button>
        </div>
      </section>


      {/* FEATURES */}
      <section className="px-6 py-20 bg-neutral-900">
        <div className="grid md:grid-cols-3 gap-6 max-w-6xl mx-auto">
          <Feature
            icon={<Wrench />}
            title="Easy Install"
            text="Designed to slide inside the shaft with a secure internal grip."
          />
          <Feature
            icon={<ShieldCheck />}
            title="Strong & Reliable"
            text="Carbon‑fiber reinforcement built for high‑impact play."
          />
          <Feature
            icon={<Zap />}
            title="Game‑Ready"
            text="Fix your stick and get back on the ice fast."
          />
        </div>
      </section>


      {/* PREORDER SECTION */}
      <section className="px-6 py-24 text-center max-w-4xl mx-auto">
        <h2 className="text-4xl font-bold">Pre‑Order Stick Fix</h2>
        <p className="mt-4 text-neutral-300">
          Be among the first to get the next‑generation hockey stick repair system.
        </p>
        <div className="mt-10">
          <Button size="lg" className="rounded-2xl px-12 text-lg">
            Reserve Yours
          </Button>
        </div>
        <p className="mt-4 text-sm text-neutral-400">
          Limited first batch • Shipping worldwide
        </p>
      </section>


      {/* FOOTER */}
      <footer className="border-t border-neutral-800 py-10 text-center text-sm text-neutral-500">
        © {new Date().getFullYear()} Stick Fix. All rights reserved.
      </footer>
    </div>
  );
}


function Feature({ icon, title, text }) {
  return (
    <Card className="bg-neutral-950 border-neutral-800 rounded-2xl shadow-lg">
      <CardContent className="p-6">
        <div className="mb-4 text-white">{icon}</div>
        <h3 className="text-xl font-semibold">{title}</h3>
        <p className="mt-2 text-neutral-400">{text}</p>
      </CardContent>
    </Card>
  );
}
