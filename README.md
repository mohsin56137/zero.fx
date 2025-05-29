import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Input } from "@/components/ui/input"; import { useState } from "react";

export default function ZeroFXLanding() { return ( <div className="min-h-screen bg-black text-white font-sans p-6"> <header className="text-center py-12"> <h1 className="text-5xl font-bold tracking-widest">ZERO.FX</h1> <p className="text-gray-400 mt-4 text-lg">Zero effetti. Solo realtà.</p> </header>

<section className="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
    <Card className="bg-zinc-900 shadow-xl rounded-2xl">
      <CardContent className="p-6">
        <h2 className="text-2xl font-semibold mb-2">Collezione Streetwear</h2>
        <p className="text-gray-400 mb-4">Autenticità pura per chi vive fuori dagli schemi. Hoodie, tee, pants & caps in edizione limitata.</p>
        <Button className="bg-white text-black hover:bg-gray-200">Scopri ora</Button>
      </CardContent>
    </Card>

    <Card className="bg-zinc-900 shadow-xl rounded-2xl">
      <CardContent className="p-6">
        <h2 className="text-2xl font-semibold mb-2">Iscriviti alla crew</h2>
        <p className="text-gray-400 mb-4">Ricevi anteprime, sconti esclusivi e novità dalla realtà ZERO.FX.</p>
        <div className="flex gap-2">
          <Input placeholder="La tua email" className="flex-1 bg-black border border-gray-700 text-white" />
          <Button className="bg-white text-black hover:bg-gray-200">Join</Button>
        </div>
      </CardContent>
    </Card>
  </section>

  <footer className="mt-16 text-center text-gray-600 text-sm">
    © 2025 ZERO.FX — No filters. No rules.
  </footer>
</div>

); }

