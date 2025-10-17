import Hero from "@/components/Hero";
import WhatIsGrid from "@/components/WhatIsGrid";
import HowItWorks from "@/components/HowItWorks";
import Features from "@/components/Features";
import NewsFeed from "@/components/NewsFeed";
import AIChat from "@/components/AIChat";
import CTA from "@/components/CTA";
import Footer from "@/components/Footer";

const Index = () => {
  return (
    <div className="min-h-screen bg-background">
      <Hero />
      <WhatIsGrid />
      <HowItWorks />
      <Features />
      <NewsFeed />
      <AIChat />
      <CTA />
      <Footer />
    </div>
  );
};

export default Index;
